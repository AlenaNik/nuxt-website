<template>
  <div>
    <Nav/>
    <nuxt />
  </div>
</template>

<script>
import Nav from './partials/nav';
export default {
  components: {
    Nav
  }
}
</script>
<style>
  body {
    box-sizing: border-box;
    height: 100%;
  }

  *,
  *:before,
  *:after {
    box-sizing: inherit;
  }



</style>
