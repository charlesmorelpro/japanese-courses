<template>
  <div id="app" class="h-screen flex items-center justify-center">
    <div class="container relative flex justify-center overflow-hidden">
      <img src="./assets/bg.jpg" alt="background" class="z-0 w-2/3 absolute top-0 right-0">
      <div class="h-24 w-24 bg-red-200 rounded-full absolute -left-10 bottom-24"></div>
      <div class="z-10 w-9/12">
        <div class="relative flex items-center justify-between mt-10">
          <img src="./assets/logo.jpg" alt="Logo" class="h-6">
          <div class="flex">
            <ul class="flex items-center">
              <li class="text-sm mx-8 font-bold">Courses</li>
              <li class="text-sm mx-8 font-bold">Why Us</li>
              <li class="text-sm mx-8 font-bold">Support</li>
            </ul>
            <button class="text-sm ml-8 px-4 py-2 border-2 border-black rounded-xl font-bold">Get Started</button>
          </div>
        </div>

        <div class="w-64 mt-20">
          <h1 class="title">Learn Japanese</h1>
          <p class="my-8">Visiting the temples in Kyoto, getting a new job, or making a personal connection 
            -no matter why you want to learn, we have the right course for you.</p>
          <button class="px-5 py-3 my-2 rounded-xl bg-indigo-900 text-yellow-100 font-semibold">Get Started</button>
        </div>

        <div class="mt-28 flex justify-start">
          <div class="theme-card">
            <img src="./assets/book.png" alt="book" class="h-10">
            <p class="mt-8">
              <span class="font-semibold">Detailed lessons</span>
              packed with vocabulary grammar culture...
            </p>
          </div>
          <div class="theme-card">
            <img src="./assets/headset.png" alt="book" class="h-10">
            <p class="mt-8">
              <span class="font-semibold">Engaging audio</span>
              featuring native speakers to perfect...
            </p>
          </div>
          <div class="theme-card">
            <img src="./assets/loop.png" alt="book" class="h-10">
            <p class="mt-8">
              <span class="font-semibold">Flexible subscription options</span>
               depending on...
            </p>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<style>
@tailwind base;
@tailwind components;
@tailwind utilities;

@font-face {
  font-family: "Habanera Bold";
  src: url('./assets/Habanera-Bold.ttf');
}

@font-face {
  font-family: "Habanera ExtraBold";
  src: url('./assets/Habanera-ExtraBold.ttf');
}

@font-face {
  font-family: "Habanera";
  src: url('./assets/Habanera-Regular.ttf');
}

* {
  margin: 0;
  padding: 0;
  list-style: none;
}

#app {
  font-family: Montserrat;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-size: 12px;
}

.container {
  width: 1200px;
  height: 700px;
  border: gray 2px solid;
}

.title {
  /* font-family: Habanera ExtraBold; */
  font-size: 52px;
  font-weight: bold;
  line-height: 46px;
}

.theme-card {
  width: 180px;
  margin-right: 74px;
}
</style>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>
