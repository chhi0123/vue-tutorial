<template>
  <div class="limiter">
    <div class="container-login100">
      <div class="wrap-login100">
        <form class="login100-form validate-form">
          <span class="login100-form-title p-b-26">
            Welcome
          </span>

          <span class="login100-form-title p-b-48">
            <i class="zmdi zmdi-font"></i>
          </span>

          <div>
            <md-field md-clearable>
              <label>Email address</label>
              <md-input v-model="initial"></md-input>
            </md-field>
          </div>

          <div>
            <md-field>
              <label>Password</label>
              <md-input v-model="password" type="password"></md-input>
            </md-field>
          </div>

          <div>
            <md-button class="md-dense md-raised md-primary">
              Login
            </md-button>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
