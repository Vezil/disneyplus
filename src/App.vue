<template>
  <div id="app" class="flex bg-gray-900 text-white min-h-screen">
    <link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet">
      <sidebar-navigation />
      
      
      
      
    <div class="w-full">
      <transition name="page" mode="out-in">
        
      <router-view/>
     </transition>
    </div>
    <FooterG />
  </div>

</template>

<script>
import SidebarNavigation from '@/components/SidebarNavigation.vue';
import FooterG from '@/components/FooterG.vue';

export default {
  components: {
    SidebarNavigation,
    FooterG
     
  }
}
</script>


<style src="./css/main.css">