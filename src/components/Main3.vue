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
      <div class="top-wrapper">
        <h2>recent causes</h2>
        <hr>
        <p>We run projects in over 30 countries in 5 continents</p>
      </div>
      <div class="bottom-wrapper">
        <div class="card">
          <img src="/images/causes-1.jpeg" alt="">
        </div>
        <div class="card">
          <img src="/images/causes-2.jpeg" alt="">
        </div>
        <div class="card">
          <img src="/images/causes-3.jpeg" alt="">
        </div>
        <div class="card">
          <img src="/images/causes-4.jpeg" alt="">
        </div>
      </div>
    </div>
    <div class="banner">
      <h3>view all our causes</h3>
    </div>
</template>

<style lang="scss" scoped>
  #container {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    height: 800px;
    padding: 100px;
    .top-wrapper {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      p {
        font-weight: lighter;
        transform: scale(1.2,1);
      }
    }
    .bottom-wrapper {
      display: flex;
      gap: 40px;
      .card {
        height: 250px;
        width: calc(100% - 200px);
        img {
          width: 100%;
        }
      }
    }
  }
  .banner {
    height: 130px;
    background-color: #ed6967;
    h3 {
      text-align: center;
      line-height: 130px;
      font-weight: lighter;
      color: white;
    }
  }
</style>