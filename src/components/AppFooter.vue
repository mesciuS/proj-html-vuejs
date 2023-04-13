<script>
export default {
  data() {
    return {

    }
  },
}
</script>

<template>
    <div id="container">
      <div class="top">
        <img src="/images/logo-small.png" alt="">
      </div>
      <div class="bottom">
        <p>&copy; Copyright 2012-2022 | Avada Theme by <span>ThemeFusion</span> | All Rights Reserved | Powered by <span>ME</span></p>
        <div class="loghi">
          <i class="fa-brands fa-facebook"></i>
          <i class="fa-brands fa-instagram"></i>
          <i class="fa-brands fa-twitter"></i>
          <i class="fa-brands fa-youtube"></i>
        </div>
      </div>
    </div>
</template>

<style lang="scss" scoped>
  #container {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    height: 200px;
    .top {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 55%;
    }
    .bottom {
      display: flex;
      flex-direction: column;
      justify-content: space-around;
      align-items: center;
      width: 100%;
      height: 45%;
      background-color: #f9f9f9;
      span {
        color: #fdd182;
      }
      .loghi {
        display: flex;
        gap: 10px;
        i {
          font-size: 2em;
          color: #fdd182;
        }
      }
    }
  }
</style>