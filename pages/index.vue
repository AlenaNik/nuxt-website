<template>
  <div class="inline-flex">
  <div class="image">
    <img src="https://images.unsplash.com/photo-1488485339565-566d63f7dbb7?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2468&q=80" alt="">
    <div class="max-w-sm rounded overflow-hidden ml-10">
      <div class="px-6 py-4 ">
        <div class="font-bold text-xl mb-2">Front-end Developer / UX Engineer </div>
        <p class="text-gray-500 text-base">
          Hey! Currently I'm working as UX/UI designer in Madrid at Next Limit. I finished my intensive 5-months training as a full-stack developer and started Software Engineering Degree at International Valencian University. I'm interested in building web applications (React and Vue), as well as designing clean UI, always keeping in mind visual design theory (typography, color, "look and feel", interaction, composition, color theory).
        </p>
      </div>
      <div class="px-6 py-4 ml-10">
        <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm text-gray-700 mr-2">Twitter</span>
        <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm text-gray-700 mr-2">Dribble</span>
        <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm text-gray-700">LinkedIn</span>
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
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.image {
  columns: 1;
  column-gap: 2rem;
  display: block;
  margin: 4rem 0;
  img {
    margin: 0 0 2rem 0;
  }
}
@media (min-width: 29em) {
  .image {
    columns: 2;
  }
}

</style>
