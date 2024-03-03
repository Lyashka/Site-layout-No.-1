<template>
  <header class="container_header">
      <a class="logo">M N T N</a>
      <div style="display: flex; flex-direction: row;">
        <a class="header_menu_equipment" href="#">Equipment</a>
        <a class="header_menu_about_us" href="#">About us</a>
        <a class="header_menu_blog" href="#">Blog</a>
      </div>
      <div style="margin-right: 4%;" class="header_account">
        <img style="position: relative;" :src="icon_account">
        <a class="header_account" style="margin-left: 5px;" href="#">Account</a>
      </div>
    </header>
</template>

<script setup lang="ts">
import icon_account from '../assets/acc.svg';
</script>

<style scoped>
.container_header{
  display: flex;
  align-items: center;
  position: absolute;
  justify-content: space-between;
  width: 1760px;
  height: 25px;
  top: 64px;
  left: 80px;
  z-index: 10;
  color:var(--color-text-white);
 
}
.logo{
  width: 130px;
  height: 24px;
  font-size: 32px;
  display: flex;
  align-items: center;
  font-family: var(--font-chronicle-display);
}
.header_menu_equipment, .header_menu_about_us, .header_menu_blog{
  text-decoration: none;
  color: var(--color-text-white);
  display: flex;
  margin-left: 30px;
  
  
  font-size: 18px;
  
}
.header_account{
  text-decoration: none;
  color: var(--color-text-white);
  font-size: 18px;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>