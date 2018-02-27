<template>
  <div class="loginColumns animated fadeInDown">
      <div class="row">

          <div class="col-md-6">
              <h2 class="font-bold">{{ title }}</h2>

              <p>{{ description }}</p>

              <img class="logo" :src="logo" />
              <p>
                  <small>{{ small_description }}</small>
              </p>

          </div>
          <div class="col-md-6">
              <div class="ibox-content">
                  <form class="m-t" role="form" action="index.html">
                      <div class="form-group">
                          <input type="email" class="form-control" placeholder="Username" required="">
                      </div>
                      <div class="form-group">
                          <input type="password" class="form-control" placeholder="Password" required="">
                      </div>
                      <button type="submit" class="btn btn-primary block full-width m-b">{{ login }}</button>

                      <a href="#">
                          <small>{{ forgot_password }}</small>
                      </a>

                      <p class="text-muted text-center">
                          <small>{{ no_account }}</small>
                      </p>
                      <a class="btn btn-sm btn-white btn-block" href="register.html">{{ create_account }}</a>
                  </form>
                  <p class="m-t">
                      <small>{{ footer_description }}</small>
                  </p>
              </div>
          </div>
      </div>
      <hr/>
      <div class="row">
          <div class="col-md-6">
              <p>{{ credits }}</p>
          </div>
          <div class="col-md-6 text-right">
             <small>{{ years }}</small>
          </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Login',
  data () {
    return {
      title: 'Welcome to Chroma Kids Nursury',
      description: 'Simple support for nursury teachers & managers',
      small_description: 'It has survived not only five centuries, but also the leap into electronic \
      typesetting, remaining essentially unchanged.',
      loginButton: 'Login',
      logo: require('../assets/logo.png'),
      forgot_password: 'Forgot password?',
      no_account: 'Do not have an account?',
      create_account: 'Create an account',
      footer_description: 'Created by Chroma Kids 2018',
      credits: 'Copyright Chroma Kids',
      years: '© 2018'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: bold;
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
p, small, h2, h1 {
  color: #faebd7;
}
p.m-t > small, form p, form small, form a{
  color: #000 !important;
}
img.logo {
  width: 50%;
}
</style>
