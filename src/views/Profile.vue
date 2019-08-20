<template >
  <div class="font-sans h-max w-max justify-center  border border-gray-700 bg-cover bg-center" :style="{ backgroundImage: `url('${background}')`}">
    <div class="palette ">
      <div class="block m-32 px-6  "><img src="@/assets/Paskuda.jpg" alt="avatar" class="rounded-lg w-64 h-64 mr-auto ml-auto shadow-custom"></div>
      <div class="w-64 h-auto ml-auto mr-auto block  border-solid border-8 border-gray-600 text-center p-4 shadow-2xl	 bg-blue-800">Name : <b>Pan</b></div>
      <div class="w-64 h-auto ml-auto mr-auto block  border-solid border-8 border-gray-600 text-center mt-6 p-4 shadow-2xl bg-blue-800	">Surname : <b>Paskuda</b></div>
      <div class="w-64 h-auto ml-auto mr-auto block  border-solid border-8 border-gray-600 text-center mt-6 p-4 shadow-2xl bg-blue-800	">Address : <b>Chlewik ul. Prosiora 52</b></div>
      <div class="w-64 h-auto ml-auto mr-auto mb-5 block  border-solid border-8 border-gray-600 text-center mt-6 p-4 shadow-2xl	bg-blue-800">Subcription : <span class="text-green-500"> <b>Active</b></span></div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      background: require('@/assets/559646.jpg')
    }
  }
}
</script>

<style>


</style>