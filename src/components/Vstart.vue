<script setup lang="ts">

</script>

<template>
  <div :class="$style.container">
    <img src="../assets/logo.svg" :class="$style.logo"/>
    <div :class="$style.content">
      <p :class="$style.p1">기숙사 커뮤니티</p>
      <p :class="$style.p2">마이도미토리 APP</p>
      <p :class="$style.p3">기숙사의 불편한 점들을 개선한 기숙사 소통 커뮤니티앱</p>
    </div>
    <img src="../assets/mainPhone.svg" :class="$style.mainPhone"/>
  </div>
</template>


<style module>
body{
  margin: 0;
  padding: 0;
  background-color: #F5F5F5;
}

.container{
  position: relative;
  display: flex;
  background: linear-gradient(#FFC61B ,#F5F5F5);
  height: 64.26vh;
}

.logo{
  width: 6.46vw;
  height: 11.48vh;
  margin-top: 11vh;
  margin-left: 8.5vw;
}

.content{
  margin-top: 12vh;
  margin-left: 1vw;
}

.p1,
.p2,
.p3{
  color: #fff;
  margin: 0;
}

.p1,
.p3{
  font-size: 25px;
}

.p1{
  margin-top: 1.2vh;
}
.p2{
  font-size: 40px;
  font-weight: bold;
}

.p3{
  position: absolute;
  margin-top: 5vh;
  left: 9vw;
  font-weight: 600;
}

.mainPhone{
  width: 42.29vw;
  height: 100vh;
}

.mainPhone{
  margin-left: 40vh;
}
</style>
