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
    <div :class="$style.wrapTeamContent">
      <p :class="$style.teamName">BackEnd 임효진</p>
      <p :class="$style.teamName">FrontEnd 박화경</p>  
      <p :class="$style.lag">React, MySQL,Spring boot3</p>
    </div>

    <!-- 2번째 screen -->
    <img src="../assets/showPhone.svg" :class="$style.showPhone"/>
    <div :class="$style.secContainer">
      <img src="../assets/logo.svg" :class="$style.secLogo"/>

      <div :class="$style.wrapCommunityContent">
        <p :class="$style.scTitle">기숙사 커뮤니티</p>
        <p :class="$style.scName">마이도미토리</p>
        <p :class="$style.scContent">Re design story</p>
        <img src="../assets/secScreenContent.svg" :class="$style.scContent1"/>
      </div>
    </div>

    <!-- 3번째 screen -->
      <img src="../assets/thScreen.svg" :class="$style.thScreen"/>
      <div :class="$style.thContainer">
        <p :class="$style.thTitle">상벌점 화면</p>
        <p :class="$style.thCategory">#한눈에  #알기 쉽게  #간편하게</p>
        <p :class="$style.thContent">상벌점을 받은 날짜, 점수, 총점 등<br/> 다양한 정보를 한 눈에 볼 수 있다.</p>
      </div>


      <!-- 4번째 scree -->
      <img src="../assets/foPhone.svg" :class="$style.foScreen"/>
      <hr :class="$style.horizontalLine"/>
      <div :class="$style.foContainer">
        <p :class="$style.foTitle">#게시판으로 소통</p>
        <p :class="$style.foContent">커뮤니티를 사용하여 기숙사 생들끼리<br/> 소통하며, 사감 선생님의 공지사항을<br/> 한눈에 볼 수 있습니다.</p>
      </div>

      <!-- 5번째 screem -->
      <img src="../assets/fifScreen.svg" :class="$style.fifScreen"/>
      <div :class="$style.fifContainer">
        <p :class="$style.fifTitle">세탁일지</p>
        <p :class="$style.fifTitle2">작성방법</p>
        <p :class="$style.fifCategory">#3단계_끝!</p>
        <p :class="$style.one">1. 세탁 가능한 시간 및  세탁기 확인 후 선택</p>
        <p :class="$style.one1">세탁 시간 및 세탁기 신청 현황을 확인</p>
        <p :class="$style.two">2. 세탁일지 작성 완료</p>
        <p :class="$style.two2">비어있는 세탁일지 칸을 선택하고<br/> 신청하면 신청 완료</p>
        <p :class="$style.three">3. 신청한 시간에 맞춰 세탁 진행</p>
        <p :class="$style.three3">신청한 시간에 맞춰 세탁기를 이용하면 끝</p>
      </div>

      <!-- 6번째 screen -->
      <img src="../assets/sixScreen.svg" :class="$style.sixScreen"/>
      <div :class="$style.wrapSixScreen">
        <p :class="$style.sixP1"># 기숙사 일정들 간편하게</p>
        <p :class="$style.sixP2">위클리와 먼슬리 캘린더로 기숙사의 특별한 일정들을 한눈에 확인 할 수 있습니다</p>
      </div>

      <!-- 마지막 화면 -->
      <img src="../assets/endScreen.svg" :class="$style.endScreen"/>
  </div>
</template>


<style module>  
body{
  margin: 0;
  padding: 0;
  background-color: #F5F5F5;
  overflow-x: hidden;
}
::-webkit-scrollbar {
  width: 0.6vw; 
}

::-webkit-scrollbar-track {
  background: #F5F5F5; 
}

::-webkit-scrollbar-thumb {
  background-color: #FFD700;
  border-radius: 10px; 
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
.p3,
.teamName,
.scTitle,
.scName{
  color: #fff;
  margin: 0;
}

.p1,
.p3,
.scTitle,
.scName{
  font-size: 27px;
}

.p1,
.scTitle{
  margin-top: 1.2vh;
}
.p2,
.scName{
  font-size: 40px;
  width: 13vw;
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

.wrapTeamContent{
  position: absolute;
  bottom: -30vh;
  margin: 1vh;
}

.teamName,
.lag{
  color: #000;
  font-size: 18px;
}

.showPhone,
.secLogo{
  position: absolute;
  margin-top: 100vh;
}

.showPhone{
  height: 57vw;
  margin-left: 50vw;

}

.secLogo,
.wrapCommunityContent{
  left: 0;
  padding: 6vw;
  padding-top: 20vh;
}

.thScreen{
  position: absolute; 
  margin-top: 210vh;
  width: 100vw;
}

.secContainer,
.thContainer,
.foScreen,
.foContainer,
.fifScreen,
.fifContainer,
.sixScreen,
.endScreen {
  position: absolute;
}


.wrapCommunityContent{
  margin-top: 100vh;
  margin-left: 6vw;
}

.scName,
.scTitle,
.scContent,
.point,
.one,
.two,
.three{
  color: #FFC61B;
  font-weight: 700;
}

.point{
  font-weight: bold;
}
.scContent,
.scContent1{
  margin-left: -5.5vw;
}
.scContent{
  font-size: 25px;
  margin-top: 11vh;
}

.scContent1{
  color:   rgba(0, 0, 0, 0.57);
  font-size: 20px;
  line-height: 2.8vh;
  margin-top: 4vh;
}

.thContainer,
.foScreen{
  margin-top: 231vh;
  margin-left: 12vw;
}

.thTitle,
.foTitle{
  font-size: 45px;
  font-weight: bold;
}

.thCategory{
  font-size: 25px;
}

.thContent{
  font-size: 20px;
}

.foScreen{
  margin-top: 330vh;
  margin-left: 60vw;
  height: 80vh;
}
.horizontalLine {
  width: 30%;
  border: 1px solid #FFC61B;
  position: absolute;
  margin-top: 355vh;
}

.foTitle{
  color: #000;
  margin-top: 357vh;
  margin-left: 16vw;
  color: #FFC61B;
}

.foContent{
  font-size: 21px;
  text-align: right;
}

.fifScreen,
.fifContainer{
  margin-top: 405vh;
  width: 100vw;
}

.fifContainer{
  text-align: right;
  right: 3vh;
  margin-top: 438vh;
}

.fifTitle,
.fifTitle2,
.fifCategory{
  font-size: 50px;
  margin: 0;
  font-weight: bold;
  color: #FFC61B;
}

.fifTitle{
  color:#fff;
}

.fifCategory{
  font-size: 40px;
  margin-top: 4vh;
  margin-bottom: 7vh;
}

.one,
.two,
.three{
  font-size: 20px;
}

.one1,
.two2,
.three3{
  margin-bottom: 3.5vh;
  font-size: 18px;
  font-weight: bold;
}

.sixScreen{
  width: 100vw;
  margin-top: 540vh;
  height: 108vh;
}

.wrapSixScreen{
  margin-top: 540vh;
}

.sixP1,
.sixP2{
  width: 40vw;
  color: #FFC61B;
  font-size: 50px;
  font-weight: bold;
  margin-left: -22vw;
}
.sixP2{
  width: 18vw;
  font-size: 30px;
  text-align: right;
  color: #000;
  font-weight: 300;
  margin-left: -17vw;
}

.endScreen{
  margin-top:647vh;
  width: 100vw;
  height: 100vh;
}

</style>
