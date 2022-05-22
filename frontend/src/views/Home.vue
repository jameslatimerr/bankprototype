<template>
    <div class="container">
        <div>
        <button type="button" class="btn  bg-light btn-block mb-4" v-on:click="goLogin()">Sign in</button>
        </div>
    </div>
</template>
<script>
export default {
  name: 'Home',
  props: {
  },
  methods:
  {
      goLogin(){
    this.$router.push('/login'); 
      }
  }
}
</script>
