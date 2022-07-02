<script>
export default {
  name: "Navbar",
};
</script>

<template>
  <nav>
    <h2>Foodie</h2>
  </nav>
</template>

<style scoped>
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0.25rem 2rem;
  background-color: var(--main-background);
  width: 100%;
  height: 4.5rem;
  font-size: 1.2rem;
  font-weight: bold;
  z-index: 1;
  position: fixed;
  top: 0;
  left: 0;
  box-sizing: border-box;
}

h2 {
  color: var(--main-white);
  cursor: pointer;
  font-family: "Dancing Script", cursive;
  font-size: 40px;
}
</style>
