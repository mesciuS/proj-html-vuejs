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
        <div class="card">
          <i class="fa-solid fa-droplet"></i>
          <h4>Clean Water</h4>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Incidunt minus dignissimos.</p>
          <button>learn more</button>
        </div>
        <div class="card">
          <i class="fa-solid fa-stethoscope"></i>
          <h4>Vaccinations</h4>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Incidunt minus dignissimos.</p>
          <button>learn more</button>
        </div>
        <div class="card">
          <i class="fa-solid fa-graduation-cap"></i>
          <h4>Education</h4>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Incidunt minus dignissimos.</p>
          <button>learn more</button>
        </div>
        <div class="card">
          <i class="fa-solid fa-wheat-awn"></i>
          <h4>Farming</h4>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Incidunt minus dignissimos.</p>
          <button>learn more</button>
        </div>
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
    justify-content: space-between;
    align-items: center;
    height: 800px;
    background-image: url("../images/header-bg.jpeg");
    background-repeat: no-repeat;
    background-size: cover;
    padding: 100px;
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
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        align-items: center;
        height: 300px;
        width: 300px;
        i {
          font-size: 3em;
          color: #fec96b;
        }
        h4 {
          font-size: 1.5em;
          font-weight: lighter;
        }
        p {
          text-align: center;
        }
        button {
          @include bottone
        }
      }
    }
  }
</style>