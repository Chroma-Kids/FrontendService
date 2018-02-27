<template>
  <main-layout>
    <toolbar-top :current="title" />
    <div class="wrapper wrapper-content">
        <div class="middle-box text-center animated fadeInRightBig">
            <h3 class="font-bold">This is page content</h3>
            <div class="error-desc">
                You can create here any grid layout you want. And any variation layout you imagine:) Check out
                main dashboard and other site. It use many different layout.
                <br><a href="/" class="btn btn-primary m-t">Dashboard</a>
            </div>
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
      title: 'Home'
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
