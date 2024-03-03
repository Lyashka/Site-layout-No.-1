<template>
   <div class="title_container">
      <div>
        <img :src="line" class="lable_content_line"> 
        <label class="lable_content_lable">A Hiking guide</label>
      </div>
      <div class="title">
        Be prepared for the Mountains and beyond!
      </div>
      <a href="#" class="scroll_down_btn">
        <div>scroll down</div>
        <img style=" position: relative;" :src="arrow">
      </a>
    </div>
</template>

<script setup lang="ts">
    import line from '../assets/line.svg';
    import arrow from '../assets/arrow.svg'
</script>

<style scoped>
.title_container{
  position: relative;
  width: 950px;
  height: 310px;
  top: 287px;
  left: 500px;
  gap: 32px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
.lable_content_line{
  width: 72px;
  height: 2px;
  top: 10px;
}
.lable_content_lable{
  position: relative;
  width: 212px;
  height: 22px;
  left: 104px;
  text-align: center;
  font-family: var(--font-gilroy);
  color: var(--color-text-yellow);
  text-transform: uppercase;
  font-size: 18px;
  font-weight: 800;
  line-height: 22px;
  letter-spacing: 6px;
  text-align: left;
}
.title{
  width: 950px;
  height: 200px;
  font-family: var(--font-chronicle-display);
  font-size: 88px;
  font-weight: 300;
  line-height: 100px;
  letter-spacing: 0em; 
  text-align: left; 
  color: var(--color-text-white);
  text-transform: capitalize;
}
.scroll_down_btn{
  text-decoration: none;
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 126px;
  height: 24px;
  display: flex;
  flex-direction: row;
  color: var(--color-text-white)
}
</style>