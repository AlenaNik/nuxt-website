<template>
  <div class="h-screen w-screen">
    <div class="flex flex-col items-center flex-1 h-full justify-center px-4">
      <div class="flex w-full sm:w-3/4 bg-white sm:mx-4" style="height: 500px">
        <div class="hidden md:block md:w-1/2 lg:w-1/2 rounded-r-lg" style="background: url('https://images.unsplash.com/photo-1487017159836-4e23ece2e4cf?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2551&q=80'); background-size: cover; background-position: center center;"></div>
        <div class="flex flex-col w-full md:w-1/2 sm:p-10">
          <div class="flex flex-col flex-1 justify-center mb-8 ml-20 md:ml-2 lg:ml-2">
            <h1 class="font-bold text-xl mb-6 text-center hover:text-indigo-400 transition-colors transition-500 transition-linear">Front-End Developer / UI Designer </h1>
                    <p class="text-gray-700 text-center text-sm mb-6 hover:text-indigo-400 transition-colors transition-500 transition-linear">
                      Hey! My name is Alena Nikolaeva and currently I'm working as UX/UI designer in Madrid at
                      <a href="http://www.nextlimit.com/" class="font-semibold">Next Limit.</a> I enjoy coding as much as designing.
                    </p>
            <p class="text-gray-700 text-center text-sm hover:text-indigo-400 transition-colors transition-500 transition-linear">
              If you'd like to be in touch, you cant find me on:
            </p>
            <div class="w-full mt-4">
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
