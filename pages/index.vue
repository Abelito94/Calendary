<template>
  <div>
    <h1>Página Principal</h1>
    <v-btn color="primary" dark @click="goToCalendar()">Ir a Calendario</v-btn>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },

  methods: {
    goToCalendar() {
      console.log("Entró");
      this.$router.push({ name: "Calendario" });
    },
  },
};
</script>

<style>
</style>