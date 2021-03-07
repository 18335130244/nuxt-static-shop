<template>
  <div>
    <div id="app">
      {{ helloWord }}
    </div>
  </div>
</template>

<script>
export default {
  name: "app",
  layout:"dark",
  data(){
    return {
      helloWord:"hello world"
    }
  },
}
</script>

<style scoped>

</style>
