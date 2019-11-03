<template>
  <div class="h-screen w-screen">
    <div class="flex flex-col items-center flex-1 h-full justify-center px-4">
      <div class="flex w-full sm:w-3/4 bg-white sm:mx-4" style="height: 500px">
        <div class="hidden md:block md:w-1/2 lg:w-1/2 rounded-r-lg" style="background: url('https://images.unsplash.com/photo-1533038590840-1cde6e668a91?ixlib=rb-1.2.1&auto=format&fit=crop&w=668&q=80'); background-size: cover; background-position: center center;"></div>
        <div class="flex flex-col w-full md:w-1/2 sm:p-10">

              <div class="text-center mt-4">
                <a class="no-underline hover:text-indigo-600 text-gray-700 text-xs transition-colors transition-300 transition-linear">
                  Also you can send me an email: <span class="font-semibold text-gray-800 hover:text-indigo-600 transition-colors transition-500-scroll transition-ease-in-out">alena.nik.digital@gmail.com</span>
                </a>
                <p class="hover:text-indigo-600 text-gray-700 text-xs transition-colors transition-300 transition-linear">or checkout my social media</p>
                <div class="w-full mt-32">
                  <div class="py-4 text-center">
                    <a href="" target="_blank">   <span class="inline-block hover:text-indigo-400 hover:bg-indigo-100 rounded-full px-3 py-1 text-sm text-gray-700 mr-2 transition-colors transition-300 transition-linear"> <font-awesome-icon :icon="['fab', 'linkedin']"/></span></a>
                    <a href="" target="_blank">   <span class="inline-block hover:text-indigo-400 hover:bg-indigo-100 rounded-full px-3 py-1 text-sm text-gray-700 mr-2 transition-colors transition-300 transition-linear"> <font-awesome-icon :icon="['fab', 'dribbble']"/></span></a>
                    <a href="" target="_blank">   <span class="inline-block hover:text-indigo-400 hover:bg-indigo-100 rounded-full px-3 py-1 text-sm text-gray-700 mr-2 transition-colors transition-300 transition-linear"> <font-awesome-icon :icon="['fab', 'github']"/></span></a>
                    <a href="" target="_blank">   <span class="inline-block hover:text-indigo-400 hover:bg-indigo-100  rounded-full px-3 py-1 text-sm text-gray-700 mr-2 transition-colors transition-300 transition-linear"> <font-awesome-icon :icon="['fab', 'twitter']"/></span></a>
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
