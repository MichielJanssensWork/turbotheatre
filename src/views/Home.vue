<template>
  <div class="background">


    <div class="wood">

    </div>
    <div class="drapes-top">

    </div>

    <div class="menu-block">
      <img class="logo" src="../../../turbotheatre_BAK/src/assets/img/turbo-theatre-logo.svg">
      <ul>
        <li><router-link to="/puppet" class="button">Start session</router-link></li>
        <li><router-link to="/puppet" class="button">Puppet list</router-link></li>
        <li><router-link to="/puppet" class="button">Options</router-link></li>
        <li><router-link to="/puppet" class="button">Credits</router-link></li>
      </ul>
    </div>

    <div class="container">
      <!--This is the artboard for the puppets-->
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'I am the home page'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
