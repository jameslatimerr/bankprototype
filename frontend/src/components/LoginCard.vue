<template>
<div class="d-flex justify-content-center">
<div class="card" style="width: 25rem;">
    <div class="container p-2">
        <h3>Login</h3>
    </div>
    <form>
  <!-- Email input -->
  <div class="form-outline p-4">
    <input type="email" id="form2Example1" class="form-control" v-model="pass"/>
    <label class="form-label" for="form2Example1">Email address</label>
  </div>

  <!-- Password input -->
  <div class="form-outline mb-4 p-4">
    <input type="password" id="form2Example2" class="form-control" v-model="this.pass" />
    <label class="form-label" for="form2Example2">Password</label>
  </div>

  <!-- 2 column grid layout for inline styling -->
  <div class="row mb-4">
    <div class="col d-flex justify-content-center">
      <!-- Checkbox -->
      <div class="form-check">
        <input class="form-check-input" type="checkbox" value="" id="form2Example31"/>
        <label class="form-check-label" for="form2Example31"> Remember me </label>
      </div>
    </div>

    <div class="col">
      <!-- Simple link -->
      <a href="#!">Forgot password?</a>
    </div>
  </div>

  <!-- Submit button -->
  <button type="button" class="btn btn-block mb-4">Sign in</button>

  <!-- Register buttons -->
  <div class="text-center">
    <p>Not a member? <a href="#!">Register</a></p>
  </div>
</form>
</div>
</div>
</template>
<script>
// import axios from 'axios'
export default {
  name: 'LoginCard',
  props: {
  },
  data (){
      return{
          user : '',
          last : ''
      }
  },
  methods: {
      
  }
}
</script>
<style scoped>
h3 {
    font-family: sans-serif;
    font-weight: normal;
}
label {
    font-family: sans-serif;
    font-weight: lighter;
}
button {
    font-family: sans-serif;
    font-weight: lighter;
    outline-color: rgb(176, 223, 176);
    background-color: rgb(176, 223, 176);
}
p {
    font-family: sans-serif;
    font-weight: lighter;
}
.container {
    background-color: rgb(176, 223, 176);
}    


</style>