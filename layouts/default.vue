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
<style scoped>
  body {
    box-sizing: border-box;
    height: 100%;
    background-color: white;
    margin: 0;
    font-family: "Helvetica Neue";
  }

  *,
  *:before,
  *:after {
    box-sizing: inherit;
    margin: 0;
  }



</style>
