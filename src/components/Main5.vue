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
      <h2>change a life today</h2>
      <hr>
      <p>As long as poverty, injustice & inequality persist, none of us can truly rest. It doesn't take much to change a life. Get in touch today and start making the difference.</p>
      <div class="btn-wrapper">
        <button>volunteer</button>
        <button>donate now</button>
      </div>
    </div>
</template>

<style lang="scss" scoped>
@mixin bottone($bg: #fec96b, $brd: none, $clr: white) {
    background-color: $bg;
    padding: 12px 25px 12px 25px;
    border: $brd;
    color: $clr;
}
  #container {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    height: 400px;
    background-image: url("../images/header-bg.jpeg");
    background-repeat: no-repeat;
    background-size: cover;
    padding: 80px;
    color: white;
    p {
      width: 600px;
      text-align: center;
      line-height: 30px;
      padding-bottom: 30px;
    }
    .btn-wrapper {
      display: flex;
      gap: 10px;
      button {
        @include bottone($bg: transparent, $brd: 2px solid white, $clr: white)
      }
    }
  }
</style>