<script>
import Navbar from "./components/Navbar.vue";

export default {
  name: "App",
  components: {
    Navbar,
  },
};
</script>

<template>
  <div class="app-container">
    <Navbar />
  </div>
</template>

<style>
@import "@/assets/base.css";

.app-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  min-height: 100vh;
  background-color: #42022e;
  width: 100vw;
  padding: 1rem;
}
</style>
