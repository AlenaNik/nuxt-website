<template>
    <header>
      <nav class="navbar fixed min-h-screen flex justify-center items-center mx-2">
        <ul>
          <li
            class="mb-10 mx-6 sm:mx-6 xs:mx-6"
          ><nuxt-link
            to="/">Home
          </nuxt-link>
          </li>
          <li
            class="mb-10 mx-6"
          ><nuxt-link
            to="/work">Work</nuxt-link></li>
          <li
            class="mb-10 mx-6"
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

<style scoped>
.navbar {
  font-family: "Helvetica Neue";
  font-size: 20px;
  font-weight: 700;
  color: black;
}
a {
  font-size: 16px;
  position: relative;
  text-decoration: none;
  padding-bottom: 8px;

  &:before,
  &:after {
    content: '';
    position: absolute;
    bottom: 2px;
    left: 0; right: 0;
    height: 2px;
    background-color: #5967d8;
  }
  &:before {
    opacity: 0;
    transform: translateY(-8px);
    transition: transform 0s cubic-bezier(0.175, 0.885, 0.320, 1.275), opacity 0s;
  }
  &:after {
    opacity: 0;
    transform: translateY(4);
    transition: transform .6s cubic-bezier(0.175, 0.885, 0.320, 1.275), opacity .2s;
  }
  &:hover,
  &:focus {
    &:before,
    &:after {
      opacity: 1;
      transform: translateY(0);
    }
    &:before {
      transition: transform .6s cubic-bezier(0.175, 0.885, 0.320, 1.275), opacity .2s;
    }
    &:after {
      transition: transform 0s .2s cubic-bezier(0.175, 0.885, 0.320, 1.275), opacity 0s .2s;
    }
  }
}

</style>
