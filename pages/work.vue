<template>
  <div class="h-screen w-screen">
    <div class="flex flex-col items-center flex-1 h-full justify-center px-4">
      <div class="flex w-full sm:w-3/4 bg-white sm:mx-4" style="height: 500px">
        <div class="hidden md:block md:w-1/2 lg:w-1/2 rounded-r-lg" style="background: url('https://images.unsplash.com/photo-1512295767273-ac109ac3acfa?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80'); background-size: cover; background-position: center center;"></div>
        <div class="flex flex-col w-full md:w-1/2 sm:p-6">
          <div class="flex flex-col flex-1 justify-center ml-20 md:ml-2 lg:ml-2">
            <h1 class="font-bold text-xl mb-6 text-center hover:text-indigo-400 transition-colors transition-500 transition-linear">Front-End Developer + UI Designer ?</h1>
           <div class="mb-4 text-xs text-gray-700 font-mono">
             <p class="hover:line-through cursor-pointer transition-transform transition-500 transition-linear">Designer: “You shouldn’t put icons on every option. This introduces a ‘Hick’s Law’ issue and the user will be way too overwhelmed.”</p>
             <p>👌Engineer: “Every one of these terms can’t be edited inline. That would overload the DOM. We need to have one single modal that opens to edit a term for efficiency.”</p>
           </div>
            <ul class="text-gray-800 text-sm mb-6 ">
              <li class="text-justify mb-4"><span class="font-semibold text-indigo-600 hover:text-indigo-800 transition-colors transition-500 transition-ease-in-out">UX/UI Desing Skills: </span>User experience research, problem statement, user interviews, pain points, customer journey mapping, storyboards, prototyping and <span class="font-semibold">design solution</span></li>
              <li class="text-justify mb-4"><span class="font-semibold text-indigo-600 hover:text-indigo-800 transition-colors transition-500-scroll transition-ease-in-out">Front-End Development: </span>Primary domain focused on the design/UI component layer of an application. Tecnology: React, Vue, Nuxt, Sass, PostCSS, Styled Components, UI Libraries (Material UI, Materialize, Reactstrap, TailwindCSS, Tachyons, Ant Design), Netlify, Node, Express, Firebase</li>
              <li class="text-justify mb-4"><span class="font-semibold text-indigo-600 hover:text-indigo-800 transition-colors transition-500-scroll transition-ease-in-out">Education: </span> <span class="font-semibold"> Full-Stack Development Bootcamp </span> - Wild Code School (2019), <span class="font-semibold">Bachelor's Degree in Computer Science and Engineering </span> - Universidad Internacional de Valencia (2019 - present) </li>
            </ul>
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
