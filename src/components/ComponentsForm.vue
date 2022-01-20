<template>
  <v-form ref="form" v-model="valid" lazy-validation class="py-md-10 px-md-10 px-7">
    <p class="font-weight-black text-md-h4 text-h5 ">CONTACTANOS</p>
    <p class="text-body-2 font-weight-medium">
      Siéntase libre de contactarnos en cualquier momento. Nos comunicaremos con
      usted lo antes posible.
    </p>
    <v-text-field
      v-model="name"
      :counter="10"
      :rules="nameRules"
      label="Nombre"
      required
    ></v-text-field>

    <v-text-field
      v-model="email"
      :rules="emailRules"
      label="Correo"
      required
    ></v-text-field>

    <v-textarea color="teal" label="Cuentanos tu idea">
      <template>
        <div>Bio <small>(optional)</small></div>
      </template>
    </v-textarea>

    <v-btn block color="black" class="white--text py-6 rounded-0" @click="validate">
      
      ENVIAR MENSAJE
      <v-icon right>
          mdi-email-fast
      </v-icon>
    </v-btn>

  </v-form>
</template>

<script>
export default {
  data: () => ({
    valid: true,
    name: "",
    nameRules: [
      (v) => !!v || "Name is required",
      (v) => (v && v.length <= 10) || "Name must be less than 10 characters",
    ],
    email: "",
    emailRules: [
      (v) => !!v || "E-mail is required",
      (v) => /.+@.+\..+/.test(v) || "E-mail must be valid",
    ],
    select: null,
    items: ["Item 1", "Item 2", "Item 3", "Item 4"],
    checkbox: false,
  }),

  methods: {
    validate() {
      this.$refs.form.validate();
    },
    reset() {
      this.$refs.form.reset();
    },
    resetValidation() {
      this.$refs.form.resetValidation();
    },
  },
};
</script>