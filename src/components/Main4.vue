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
        <h2>latest articles</h2>
        <hr>
        <p>Together we make all the difference</p>
      </div>
      <div class="bottom-wrapper">
        <div class="left">
          <div class="img-wrapper">
            <img src="/images/latest-1.jpeg" alt="">
          </div>
          <div class="text-wrapper">
            <strong>Understanding community complexities</strong>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aut ipsam saepe.</p>
          </div>
        </div>
        <div class="right">
          <div class="line">
            <div class="line-img">
              <img src="/images/causes-1.jpeg" alt="">
            </div>
            <div class="line-text">
              <strong>The human story of uniqueness</strong>
              <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Fuga repellendus tempore.</p>
            </div>
          </div>
          <div class="line">
            <div class="line-img">
              <img src="/images/causes-2.jpeg" alt="">
            </div>
            <div class="line-text">
              <strong>Sustainable trade tattics</strong>
              <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Fuga repellendus tempore.</p>
            </div>
          </div>
          <div class="line">
            <div class="line-img">
              <img src="/images/causes-3.jpeg" alt="">
            </div>
            <div class="line-text">
              <strong>Farmers making a difference</strong>
              <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Fuga repellendus tempore.</p>
            </div>
          </div>
          <div class="line">
            <div class="line-img">
              <img src="/images/causes-4.jpeg" alt="">
            </div>
            <div class="line-text">
              <strong>Meeting remote tribes in Peru</strong>
              <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Fuga repellendus tempore.</p>
            </div>
          </div>
        </div>
      </div>
      <div class="banner">
        <h3>view all our articles</h3>
      </div>
    </div>
</template>

<style lang="scss" scoped>
  #container {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    height: 1000px;
    padding: 100px 250px 100px 250px;
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
      width: 100%;
      display: flex;
      gap: 60px;
      padding-top: 50px;
      padding-bottom: 50px;
      .left {
        width: 50%;
        height: 500px;
        border: 2px solid #e5e5e5;
        border-bottom-style: outset;
        .img-wrapper {
          width: 100%;
          img {
          width: 100%;
          }
        }
        .text-wrapper {
          padding: 20px;
          p {
            padding-top: 20px;
            line-height: 30px;
          }
        }
      }
      .right {
        display: flex;
        flex-direction: column;
        width: 50%;
        gap: 25px;
        height: 500px;
        .line {
          display: flex;
          gap: 25px;
          .line-img {
            height: 100px;
            img {
              height: 100%;
            }
          }
          .line-text {
            padding-top: 10px;
            p {
              padding-top: 10px;
              line-height: 30px;
            }
          }
        }
      }
    }
    .banner {
      width: 100%;
      height: 50px;
      background-color: #ed6967;
      h3 {
        text-align: center;
        line-height: 50px;
        font-weight: lighter;
        color: white;
      }
    }
  }
</style>