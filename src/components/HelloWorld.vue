<template>
  <div class="root_container">

    <hello-mark-down>

    </hello-mark-down>

  </div>
</template>

<script>
  import HelloMarkDown from './HelloMarkDown'


export default {
  name: 'HelloWorld',

  components:{
    HelloMarkDown
  },

  data () {
    return {
    }
  }
}
</script>

<style scoped>
  .root_container {
  }
</style>
