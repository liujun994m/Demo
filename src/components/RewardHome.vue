<template>
  <div class ="RewardHome">
    <div class="Top">  <!--将页面分成三个部分，此部分为Top-->
      <div class ="RewardTopPhi">
        <img src ="../assets/phicomm.png">
      </div>
      <div class ="RewardTop1">
        <img src ="../assets/1.png">
      </div>
      <div class ="RewardTopWifi">
        <img src ="../assets/logo.png">
      </div>
    </div>

    <div class ="Mid">  <!--此部分为中间部分Mid-->
      <img src ="../assets/invalid-name.png">
    </div>

    <div class="End">  <!--此部分为顶部部分End-->

      <div class ="EndCopyright">

      </div>
    </div>
  </div>
</template>

<script>
    export default {
        name: "RewardHome"
    }

</script>

<style scoped>
  .RewardHome
  {
    height :1080px;
    width :1920px;
  }
  .Top
  {
    display: -webkit-box;
    height :106px;
    width :1920px;
    -webkit-box-orient : horizontal;
  }
  .RewardTopPhi
  {
    position: relative;
    left: 41px;
    top: 46px;
    height :20px;
    width :150px;
  }
  .RewardTop1
  {
    position: relative;
    left: 211px;
    top: 45px;
    height :22px;
    width :1px;
  }
  .RewardTopWifi
  {

    position: relative;
    left: 232px;
    top: 42px;
    height :26px;
    width :100px;
  }
  .Mid
  {
    height :580px;
    width :1920px;
  }
  .End
  {
    height :394px;
    width :1920px;
  }

  .EndCopyright
  {
    position: relative;
    top: 337px;
    height :57px;
    width :1920px;
    background-color: #494949;
  }
</style>
