<template>
  <div class="row wrapper border-bottom white-bg page-heading">
    <div class="col-lg-10">
        <h2>{{ current }}</h2>
        <ol class="breadcrumb">
<!--             <li>
              <router-link to="/login">
                Home
              </router-link>
            </li> -->
            <li class="active">
                <strong>{{ current }}</strong>
            </li>
        </ol>
    </div>
    <div class="col-lg-2">

    </div>
  </div>
</template>

<script>
export default {
  props: ['current'],
  data () {
    return {
      welcome_user: 'Welcome to Chroma Kids for Nursury'
    }
  }
}
</script>

<style scoped>
    p{
      color: white;
    }
</style>
