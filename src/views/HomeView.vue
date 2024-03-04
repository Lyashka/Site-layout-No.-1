<template>
  <div class="container">   
    <Header/>
    <Social/>
    <img class="HG" src="https://s3-alpha-sig.figma.com/img/e35d/ee6d/eae63c1dba994d043f4de7eaf83ad2f4?Expires=1710115200&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=ndnbA98dpQFI3cn34VRfa1AlmhmUInlJLwssXXfAD-lzZL2db80f0-ovX7HmazUqHM473w6bLNb~sTIKz602pRWubS0sCCsIa7L9amZw99x2xra86XHeEFmly8gHt1k5IYV5r4NFtElAn5xy8wSPxBqRykCKjGr92C3QpPBMAEPYnHkftqPxwn2nuvZoGnwQrJc0SbZqV6fKc1oiTKf7tA3xkuvArPoJ9irwXub94tD37~qn6-0~JZftiw1-2Z4ZDBRPud9OKZ6TbSdbxGCv1JPFSpNPiaRkcoxNZJs0-pK~lyE334lT2NA6HEA8PovX32ZZ39ELViHuTWCKMqWcxA__" alt="">
    <div class="bgHero"></div>
    <img class="MG" src="https://s3-alpha-sig.figma.com/img/9c12/887c/275a251d0966ae77b7e58d007b190a88?Expires=1710115200&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=iSti0gQNz3LZBl6GTRywY2WBCIhkrJdDPW6yFng1xghqROzE-G2eeOcz3llgCYfg1KGb36Ex8VELFxiGHQb7Vw4f6ClUsQJNgogmUqUsA6f~ilgrRgrgZi3umIrbXRXuld9EbcLhW3EU2NrYnPrxZHePRBQhR3wFdLlyW~JJKexrwAY21U05ggmFz4FHAv4FQ80fzYVxP8hf7tAC7YfL4Buue61wGlbrlF9AVS6R2zlLtLqkevJbTKGIIrk3eh-07X7~o8jIBy3MHswP1zY048g9G0ZguJ2RngS3MvsYbG779WcsLG1REHn2D9idZ3To75SB6my67acp0eeo7GVopQ__" alt="">
    <img class="VG" src="https://s3-alpha-sig.figma.com/img/d13c/a5ea/79047419a4bc27738c3cc555a99dcd2c?Expires=1710115200&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=cHaEq5eQ34HY8sxvkFtLzsGf1aly2oX2vZAK2UDSnevBmrme8NjuKrjnJZJEZNC91lt7zum~dnDe-m9~qjG7Rq~iBncOef-Qj6jzKOCQw1WMAcRK-jkAo0lceQ88ZpEYSXAL3yKghXEr1CTsbIOnNbXyBikvIKdWYCbs-MDO23tA6M~1Os~BS-jkld6ZSRPX5fCIrmgv-74FDTGEJG7mmEdEmRkqM1K-Zyho3xMhH6uHZy0RuzqO9QVn2u05~AM9SQadhX4mlrPlZPHc~ZgfOXHxCILkLJx8TZwiWH9Rtn1dlhapOUJR27-zy3xmDHiyUxE--crjOOFsoE~XR68h8Q__" alt="">
    <div class="BG_Content"></div>
    <Title/>
  
    <div class="main_content">
      <div class="content_1">
        <div class="content_1_text_container">
          <img class="content_1_number_bg" :src="number_01_icon">

          <div class="content_1_main_text_ccontainer">
              <div class="content_1_main_prev">
                <img class="content_1_main_text_img" style="position: static;" :src="line">
                <div class="content_1_main_text_lable">Get Started</div>
              </div>
              <div class="content_1_text">What level of  hiker are you?</div>
              <div class="content_1_description_text">Determining what level of hiker you are can be an important tool when planning future hikes. This hiking level guide will help you plan hikes according to different hike ratings set by various websites like All Trails and Modern Hiker. What type of hiker are you – novice, moderate, advanced moderate, expert, or expert backpacker? </div>
              <a href="#" class="scroll_more_btn">
                <div>read more</div>
                <img style="position: relative;" :src="arrow2">
              </a>
          </div>
        </div>
        <img class="content_1_img" src="https://s3-alpha-sig.figma.com/img/2d2c/0c03/0d05d27b864b5ad081fea6d54702a838?Expires=1710115200&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=iNtDZm941aY~I2Hf1bJ9b7LynkK0vtSHeP-tKWhLg2OYz~4pYHnNDR09sjK2FRDo8PFg-siyN3bMKEIiQdz9xVOm8XGbcmJ5R6S3uPLW7f1m~Qwk15uxG0TDmeKRuVFoRTgFLpFIuZSoUvQXzc4A5Z2nE9m~zj5YmWMMuz4hHz9ycmNyspWruzjmYAzN7vco6PDmTBdXiDR2OCdrts4U8h~MLr6ciStX0g1XBUH4FqOmkR1UyuYnAnNmbuHSQB3iUxhGwsQi7-OgxDXIBqYTTkluotBzqOKV6x2WHHlAzY04BRtITke7PzzZ9iiNRYjc5P0KYVvMPc~iHle~r13c4A__">
      </div>

      <div class="content_2"></div>
      <div class="content_3"></div>
    </div>
   

  </div>
</template>

<script setup lang="ts">
import Header from '../components/Header.vue';
import Social from '../components/Social.vue';
import Title from '../components/Title.vue'

import number_01_icon from '../assets/number_01.svg'
import line from '../assets/line.svg'
import arrow2 from '../assets/arrow2.svg'
</script>

<style scoped>
.bgHero{
  position: absolute;
  width: 100%;
  height: 1200px;
  background: linear-gradient(330.24deg, rgba(11, 29, 38, 0) 31.06%, #0B1D26 108.93%);
  z-index: 0;
  pointer-events: none;
}
.container{
  position: relative;
  width: 100%;
}
img{
  position: absolute;
 
}
.MG{
  width: 100%;
  height: 1422px;
  top: 464px;
  pointer-events: none;
}
.HG{
  width: 100%;
  height: 1513px;
  top: -400px;
  pointer-events: none;
}
.VG{
  width: 100%;
  height: 926px;
  top: 768px;
  pointer-events: none;
}
.BG_Content{
  position: absolute;
  width: 100%;
  height: 700px;
  top: 1200px;
  background: linear-gradient(180deg, rgba(11, 29, 38, 0) 0%, #0B1D26 61.38%);
  pointer-events: none;
}


.main_content{
  position: relative;
  width:80%;
  top: 1100px;
  margin: auto;
  border: 1px solid aqua;
  height: 1000px;

}

.content_1{
  position: relative;
  height: 720px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.content_1_text_container{
  position: relative;
  width: 100%;
  color:aliceblue;
  
}
.content_1_number_bg{
  position: absolute;
  width: 240px;
  height: 240px;
  top: 38px;
  opacity: 0.1px;
  font-size: 240px;
  font-weight: 700;
  line-height: 240px;
  letter-spacing: 0px;
  text-align: left;
  font-family: var(--font-gilroy);
  color: rgba(255, 255, 255, 0.1);


}

.content_1_main_prev{
  display: flex;
  flex-direction: row;
  align-items: center;
}

.content_1_main_text_ccontainer{
  position: relative;
  width: 632px;
  height: 439px;
  top: 141px;
  left: 150px;
  gap: 27px;
  border: 1px solid aqua;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
 
}
.content_1_main_text_img{
  /* position: relative; */
  width: 72px;
  height: 2px;
}
.content_1_main_text_lable{
  position: relative;
  width: 220px;
  height: 22px;
  left: 40px;
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

.content_1_img{
  position: relative;
  width: 566px;
  height: 720px;
}

.content_1_text{
  width: 555px;
  height: 154px;
  font-family: var(--font-chronicle-display);
  font-size: 64px;
  font-weight: 300;
  line-height: 76.8px;
  text-align: left; 
  color: var(--color-text-white);
  Word-spacing: 10px
}
.content_1_description_text{
  width: 632px;
  height: 160px;
  font-size: 18px;
  font-weight: 700;
  line-height: 32px;
  letter-spacing: 0px;
  text-align: left;

}

.scroll_more_btn{
  text-decoration: none;
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 116px;
  height: 24px;
  display: flex;
  flex-direction: row;
  color: var(--color-text-yellow)
}
</style>