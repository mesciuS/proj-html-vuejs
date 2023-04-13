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
        <h2>our values</h2>
        <hr>
        <p>Think Big. Act Bigger.</p>
      </div>
      <div class="bottom-wrapper">
        <div class="card"></div>
        <div class="card"></div>
        <div class="card"></div>
        <div class="card"></div>
      </div>
    </div>
</template>

<style lang="scss" scoped>
  #container {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    height: 800px;
    background-image: url("../images/header-bg.jpeg");
    background-repeat: no-repeat;
    background-size: cover;
    padding: 130px;
    color: white;
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
        border: 1px solid red;
        height: 350px;
        width: 300px;
      }
    }
  }
</style>