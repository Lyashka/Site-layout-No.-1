<template>
    <div class="social">
      <label class="social_lable">Follow us</label>
      <a href="#"><img style="position: relative; font-size: 50px;" :src="icon_instagram"></a>
      <a href="#"><img style="position: relative" :src="icon_twitter"></a>
    </div> 
</template>

<script setup lang="ts">
import icon_instagram from '../assets/instagram_icon.svg';
import icon_twitter from '../assets/tvitter_icon.svg'
</script> 

<style scoped>
.social{
  position: absolute;
  z-index: 10;
  color:var(--color-text-white);
  display: flex;
  flex-direction: column;
  width: 24px;
  height: 130px;
  top: 359px;
  left: 80px;
  padding: 0px, 0px, 0px, 0px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  
}
.social_lable{
  position: relative; 
  transform: rotate(90deg);
  min-width: 90px;
  font-style: normal;
  line-height: normal;
  font-size: 18px;
  margin-bottom: 30px;
}
</style>