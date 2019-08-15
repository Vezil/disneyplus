<template>
  <div id="app" class="flex bg-gray-900 text-white min-h-screen">
    <link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet">
    <div class="nav w-24 fixed bg-blue-500 min-h-screen flex justify-center items-center">
      sidebar goes here
    </div>
    <div class="w-full">
      <router-view/>
    </div>
  </div>
</template>

<style src="./css/main.css">