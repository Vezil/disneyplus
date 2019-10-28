<template>
  <FooterG>
      <div class="footerr page-footer p-2">© 2019 Copyright: Szymon Wojaczek&nbsp;&nbsp;<a href="https://github.com/Vezil/" target="_blank">Github</a></div>
  </FooterG>
</template>

<script>
import FooterG from './FooterG'
export default {
  components: {
    FooterG
  }
  
}
</script>

<style>

.footerr{
  background: black;
  color:gray;
  position:fixed;
  bottom:0;
  left:0;
  right:0;
  opacity:0.7;
  text-align:center;
}

.footerr a{
  color:lightblue;
}


</style>