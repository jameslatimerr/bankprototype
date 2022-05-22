<template>
  <div class="home">
    <RegisterCard/>
  </div>
</template>

<script>
import RegisterCard from '../components/RegisterCard.vue'
// @ is an alias to /src

export default {
  name: 'Register',
  components: {
    RegisterCard
  }
}
</script>
<style scoped>
.home{
  margin: 0;
  height: 100%;
}
</style>
