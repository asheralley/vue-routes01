<template>
  <div class="firstroute">
    <h2>{{msg}}</h2>
    Hello {{ $route.params.name }}
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'FirstRoute',
  data () {
    return {
      msg: 'This is the first route... yay XD'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
