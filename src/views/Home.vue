<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />

    <div>
      <router-link to="/dashboard" class="btn"
        >Click to enter dashboard</router-link
      >
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {};
</script>

<style scoped>
.btn {
  background-color: green;
  border-radius: 2rem;
  text-decoration-line: none;
  padding: 2vmin;
  margin-top: 2vmin;
}
</style>
