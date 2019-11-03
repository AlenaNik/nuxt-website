<template>
  <div class="h-screen w-screen">
    <div class="flex flex-col items-center flex-1 h-full justify-center px-4">
      <div class="flex w-full sm:w-3/4 bg-white sm:mx-4" style="height: 500px">
        <div class="hidden md:block md:w-1/2 lg:w-1/2 rounded-r-lg" style="background: url('https://images.unsplash.com/photo-1516962215378-7fa2e137ae93?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2468&q=80'); background-size: cover; background-position: center center;"></div>
        <div class="flex flex-col w-full md:w-1/2 sm:p-10">
              <div class="text-center mt-4">
                <a class="no-underline hover:text-indigo-600 text-gray-700 text-sm transition-colors transition-300 transition-linear">
                  You can send me an email to: <span class="font-semibold text-gray-800 hover:text-indigo-600 transition-colors transition-500-scroll transition-ease-in-out">alena.nik.digital@gmail.com</span>
                </a>
                <div class="w-full mt-32">
                  <div class="py-4 text-center">
                    <a href="https://www.linkedin.com/in/alenanikolaeva/" target="_blank">   <span class="inline-block hover:text-indigo-400 hover:bg-indigo-100 rounded-full px-3 py-1 text-sm text-gray-700 mr-2 transition-colors transition-300 transition-linear"> <font-awesome-icon :icon="['fab', 'linkedin']"/></span></a>
                    <a href="https://dribbble.com/alenanik_" target="_blank">   <span class="inline-block hover:text-indigo-400 hover:bg-indigo-100 rounded-full px-3 py-1 text-sm text-gray-700 mr-2 transition-colors transition-300 transition-linear"> <font-awesome-icon :icon="['fab', 'dribbble']"/></span></a>
                    <a href="https://github.com/AlenaNik" target="_blank">   <span class="inline-block hover:text-indigo-400 hover:bg-indigo-100 rounded-full px-3 py-1 text-sm text-gray-700 mr-2 transition-colors transition-300 transition-linear"> <font-awesome-icon :icon="['fab', 'github']"/></span></a>
                    <a href="https://twitter.com/alenanik11" target="_blank">   <span class="inline-block hover:text-indigo-400 hover:bg-indigo-100  rounded-full px-3 py-1 text-sm text-gray-700 mr-2 transition-colors transition-300 transition-linear"> <font-awesome-icon :icon="['fab', 'twitter']"/></span></a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
</template>

<script>


  export default {

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
</style>
