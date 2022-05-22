<template>
  <div class="home">
    <LoginCard/>
  </div>
</template>

<script>
// @ is an alias to /src
import LoginCard from '../components/LoginCard.vue'

export default {
  name: 'Login',
  components: {
    LoginCard
  }
}
</script>
<style scoped>
.home{
  margin: 0;
  height: 100%;
}
</style>
