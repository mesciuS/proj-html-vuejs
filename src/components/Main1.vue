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
      <div class="left">
        <h2>every moment counts</h2>
        <hr>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos, totam earum at veniam amet non ad perspiciatis reprehenderit ex doloribus fugit ullam quo quod ex doloribus fugit ullam quo quod.</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos, totam earum at veniam amet non ad perspiciatis reprehenderit ex doloribus fugit ullam quo quod, itaque nobis deserunt tenetur corrupti ipsa! itaque nobis deserunt tenetur corrupti ipsa! itaque nobis deserunt tenetur corrupti ipsa! itaque nobis deserunt tenetur corrupti ipsa!</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos, totam earum at veniam amet non ad  perspiciatis perspiciatis verit.</p>
        <button>our mission</button>
      </div>
      <div class="right">
        <div class="right-wrapper">
          <div class="wrapper-top">
            <i class="fa-regular fa-heart"></i>2032
          </div>
          <div class="wrapper-bottom">
            Volunteers worldwide
          </div>
        </div>
        <div class="right-wrapper">
          <div class="wrapper-top">
            <i class="fa-solid fa-earth-americas"></i>132
          </div>
          <div class="wrapper-bottom">
            Active projects
          </div>
        </div>
        <div class="right-wrapper">
          <div class="wrapper-top">
            <i class="fa-solid fa-dollar-sign"></i>3.8M
          </div>
          <div class="wrapper-bottom">
            Donated
          </div>
        </div>
      </div>
    </div>
</template>

<style lang="scss" scoped>
@mixin bottone($bg: #fec96b, $brd: none, $clr: white) {
    background-color: $bg;
    padding-top: 12px;
    padding-bottom: 12px;
    padding-left: 25px;
    padding-right: 25px;
    border: $brd;
    color: $clr;
}
  #container {
    display: flex;
    height: 600px;
    .left {
      width: 65%;
      padding: 100px;
      h2 {
        font-weight: lighter;
        letter-spacing: 5px;
      }
      hr {
        width: 20%;
        height: 3px;
        margin-top: 30px;
        margin-bottom: 30px;
        border: none;
        background-color: #fec96b;
      }
      p {
        line-height: 40px;
        padding-bottom: 20px;
      }
      button {
        @include bottone;
      }
    }
    .right {
      display: flex;
      flex-direction: column;
      justify-content: space-around;
      align-items: center;
      width: 35%;
      padding: 60px;
      color: white;
      background-color: #ef6966;
      .right-wrapper {
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
        .wrapper-top {
          font-size: 3em;
          letter-spacing: 3px;
        }
        .wrapper-bottom {
          font-size: 1.3em;
        }
      }
    } 
  }
</style>