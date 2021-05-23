<template>
  <h1>{{ title }}</h1>
  <Modal header='Sign up for the Giveaway!' text="Grab your ninja"/>
</template>

<script>
import Modal from "./components/Modal.vue";

export default {
  name: "App",
  components: { Modal },
  data() {
    return {
      title: "My first vue app",
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
h1 {
  border-bottom: 1px solid rgba(0, 0, 0, 0.205);
  display: inline-block;
  padding-bottom: 10px;
}
</style>
