<template>
  <main-layout>
    <toolbar-top :current="title" />
    <div class="wrapper wrapper-content">
        <div class="middle-box text-center animated fadeInRightBig">
            <h3 class="font-bold">Login</h3>
        </div>
    </div>
  </main-layout>
</template>

<script>

import mainLayout from '../layouts/Main.vue'
import ToolbarTop from '../components/toolbar'

export default {
  data () {
    return {
      title: 'Login'
    }
  },
  components: {
    mainLayout,
    ToolbarTop
  }
}
</script>

<style scoped>
  p{
    color:white
  }
</style>
