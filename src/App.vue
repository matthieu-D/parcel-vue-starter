<!-- ./src/App.vue -->
<template>
  <h1>
    Our Vue app is running {{status}}!
  </h1>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      status: 'well'
    }
  }
}
</script>
<style>
  h1 {
    text-align: center;
    font-size: 300%;
  }
</style>


