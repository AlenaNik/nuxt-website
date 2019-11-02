<template>
    <header>
      <nav class="navbar nav w-16 fixed min-h-screen flex justify-center items-center">
        <ul>
          <li
            class="mb-10 ml-6"
          ><nuxt-link
            to="/">Home</nuxt-link></li>
          <li
            class="mb-10  ml-6"
          ><nuxt-link
            to="/showcase">Work</nuxt-link></li>
          <li
            class="mb-10  ml-6"
          ><nuxt-link
            to="/contact">Contact</nuxt-link></li>
        </ul>
      </nav>
    </header>
</template>

<script>
  export default {
    name: 'Nav'
  }
</script>

<style>
.navbar {
  color: black;
  font-family: "Helvetica Neue";
  font-size: 16px;
  font-weight: 700;
}

</style>
