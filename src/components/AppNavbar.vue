<template>
  <div class="app-navbar flex justify-between items-center">
    <div>
      <router-link to="/">
        <img src="../assets/dent-tech-logo.jpeg" width="200" height="100" class="rounded-xl" alt="">

      </router-link>
      </div>
    <div>
      <nav class="mr-10 text-white text-xl font-semibold space-x-2">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/gallery">Gallery</router-link>
    </nav>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {

    }
  }
 }
</script>

<style scoped>
.app-navbar {
  background-color: #221B1B;
}

</style>
