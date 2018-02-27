<template>
  <main-layout>
    <div class="wrapper wrapper-content">
        <div class="middle-box text-center animated fadeInRightBig">
            <h3 class="font-bold">ERROR 404</h3>
            <p>UPSSS!!!</p>
        </div>
    </div>
  </main-layout>
</template>
<script>

import navigationTop from '../components/navigation'
import headerTop from '../components/header'
import footerTop from '../components/footer'

export default {
	data(){
    return {

    }
  },
  components: {
		navigationTop,
		headerTop,
		footerTop
  }
}
</script>



<style scoped>
  p{
    color:white
  }
</style>
