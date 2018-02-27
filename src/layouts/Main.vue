<template>
  <div id="wrapper">
    <navigation-top />
    <div id="page-wrapper" class="gray-bg">
      <header-top />
      <slot></slot>
    </div>
  <footer-top />
  </div>
</template>

<script>
import NavigationTop from '../components/navigation'
import HeaderTop from '../components/header'
import FooterTop from '../components/footer'
import Link from '../components/Link.vue'

export default {
  components: {
    NavigationTop,
    HeaderTop,
    FooterTop,
    Link
  }
}
</script>

<style scoped>

</style>
