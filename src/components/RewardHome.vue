<template>
  <div class="RewardTopPhi">
    <img src="./assets/phicomm.png">
    <router-view/>
  </div>
  <div class="RewardTopWifi">
    <img src="./assets/logo.png">
    <router-view/>
  </div>
  <div class="RewardMid">
    <img src="./assets/invalid-name.png">
    <router-view/>
  </div>
</template>

<script>
    export default {
        name: "RewardHome"
    }
</script>

<style scoped>

</style>
