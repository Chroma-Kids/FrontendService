<template>
  <div class="footer">
    <div>
      <strong>{{ copyright }}</strong> {{ company }}
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      copyright: 'Copyright',
      company: 'Chroma Kids 2018'
    }
  }
}
</script>

<style scoped>
  p{
    color: white;
  }
</style>
