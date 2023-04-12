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
        <div class="links">
            <div>
                <img src="images/logo-mid-white.png" alt="white-logo">
            </div>
            <ul>
                <li>home</li>
                <li>mission</li>
                <li>causes<i class="fa-solid fa-chevron-down"></i></li>
                <li>journal</li>
                <li><button>donate</button></li>
            </ul>
        </div>
        <div class="side-btns">
            <div class="prebuilts">
                <i class="fa-solid fa-folder-open"></i>
                <p>Prebuilts</p>
            </div>
            <div class="on-sale">
                <div class="wrapper">
                    <i class="fa-solid fa-dollar-sign dollaro"></i>
                    <i class="fa-solid fa-4 quattro"></i>
                    <i class="fa-solid fa-5 cinque"></i>
                </div>
                <p>On Sale</p>
            </div>
        </div>
        <div class="title">
            <h1>make a difference</h1>
            <p>As long as poverty, inustice & inequality persist, none of us can truly rest</p>
            <div class="bottom-btns">
                <button class="btn-left">our mission</button>
                <button class="btn-right">donate now</button>
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
        position: relative;
        width: 100vw;
        height: 90vh;
        background-image: url("../images/header-bg.jpeg");
        background-repeat: no-repeat;
        background-size: cover;
        padding-top: 40px;
        padding-bottom: 40px;
        padding-left: 60px;
        padding-right: 60px;
        color: white;
        .links{
            display: flex;
            justify-content: space-between;
            img {
                width: 80%;
            }
            ul {
                display: flex;
                align-items: center;
                gap: 50px;
                button {
                    @include bottone;
                }
            }

        }
        .side-btns {
            .prebuilts {
                position: absolute;
                right: 20px;
                top: 145px;
                i {
                    color: #0f111a;
                    font-size: 1.5em;
                }
            }
            .on-sale {
                position: absolute;
                right: 20px;
                top: 200px;
                .wrapper {
                    position: relative;
                    i {
                        color: #65bc7b;
                    }
                    .quattro, .cinque {
                        font-size: 1.5em;
                    }
                    .dollaro {
                        position: absolute;
                        top: 1px;
                        left: -8px;
                    }
                }
            }
            .prebuilts, .on-sale {
                display: flex;
                flex-direction: column;
                justify-content: space-around;
                align-items: center;
                height: 50px;
                width: 50px;
                border-radius: 5px;
                padding: 3px;
                font-size: .7em;
                background-color: white;
                color: black;
                cursor: pointer;
            }
        }
        .title {
            position: absolute;
            right: calc(50% - 668.517px / 2);
            top: calc(50% - 172.2px / 2);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            gap: 20px;
            h1 {
                font-size: 4em;
                font-weight: 100;
            }
            p {
                transform: scale(1.2,1);
            }
            .bottom-btns {
                display: flex;
                gap: 10px;
                .btn-left {
                    @include bottone($bg: transparent, $brd: 2px solid white, $clr: white)
                }
                .btn-right {
                    @include bottone($bg: transparent, $brd: 2px solid #fec96b, $clr: #fec96b)
                }
            }

        }
    }
</style>