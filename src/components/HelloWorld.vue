<template>
  <div class="hello">
    <div class="box">
      <header class="head">
        <nav class="navbar">
          <ul class="ul1">
            <li><a href="#one">About</a></li>
            <li><a href="#two">Tokenomics</a></li>
          </ul>
          <div class="log">
            <a href="#">
              <img src="../assets/login.png">
            </a>
          </div>
          <ul class="ul2">
            <li><a href="#three">Roadmap</a></li>
            <li @click="add" style="cursor:pointer;"><a>Connect</a></li>
          </ul>
        </nav>
      </header>
      <img class="h1" src="../assets/1.png">
      <img class="dog" src="../assets/2.png">
      <img class="dog_house" src="../assets/3.png">
      <img class="coin" src="../assets/4.png">
      <div class="social_links">
        <a target="_blank" href="https://t.me/PogeXerc"><img src="../assets/dianb.png"></a>
        <a target="_blank" href="https://twitter.com/pogexcoin?s=21&t=OGWZ0WBUiJOQDmfglImMtg"><img
            src="../assets/tt.png"></a>
      </div>
    </div>
    <div class="luse" id="one">
      <div class="left">
        <h2 class="colorHeading" :style="{ color: textColor }">What is pogex?</h2>
        <p>PogeX aims to build the first Centralized Exchange focusing primarily on Memecoins trading through Spot and
          Derivatives.</p>
        <p>Our plan is to bring normies into the memecoin market directly to help push the idea of Memecoins mostly and
          Cryptocurrencies forward.</p>
      </div>
      <div class="right">
        <img src="../assets/5.png">
      </div>
    </div>
    <div class="about_2">
      <div class="about2_wrap">
        <div class="left1">
          <img src="../assets/6.png">
        </div>
        <div class="right1">
          <p>
            Memecoins are a fun way to explore the crypto industry. With the creation of the first memecoin Dogecoin, a
            lot of people flooded the market due to its memetic nature and entertainment. Same way Shiba Inu, Floki and
            recently Pepe Memecoins have also onboarded a new set of cryptoholics into the space! Are you looking for the
            latest Memecoins with huge upside potential to trade with cheap fees?PogeX will be the place!
          </p>
        </div>
      </div>
    </div>
    <div class="roadmap" id="three">
      <img src="../assets/7.png">
      <div class="road_wrap">
        <div style="background: #A89E01;" class="road_box">
          <h3>pHASE I</h3>
          <ul>
            <li>Creation of Website & details about PogeX</li>
            <li>Contract Creation & deployment</li>
            <li>Creation of PogeX CEX Social Media accounts</li>
            <li>Creation of Whitepaper</li>
            <li>Update of Website</li>
            <li>Work on Initial Marketing towards the token offering of $POGEX</li>
          </ul>
        </div>
        <div style="background: #EB5F46;" class="road_box">
          <h3>pHASE II</h3>
          <ul>
            <li>International Billboard campaigns</li>
            <li>Chinese & Asia marketing campaigns</li>
            <li>List $POGEX on various CEX.</li>
            <li>Regular Buyback & Burn Events to increase value of $POGEX</li>
            <li>Partnerships with other big Crypto projects which will be listed on PogeX CEX</li>
          </ul>
        </div>
        <div style="background: #7B983E;" class="road_box">
          <h3>pHASE III</h3>
          <ul>
            <li>Dextools, DexScreener, etc details update</li>
            <li>AMAs & Spaces with big Crypto Communities & influencers to promote PogeX CEX.</li>
            <li>Apply for CoinMarketCap & CoinGecko listing</li>
            <li>Begin work on PogeX CEX App</li>
            <li>Listing of PogeX CEX App on Playstore & AppStore</li>
          </ul>
        </div>
        <div style="background: #45699B ;" class="road_box">
          <h3>pHASE IV</h3>
          <ul>
            <li>International Billboard campaigns</li>
            <li>Chinese & Asia marketing campaigns</li>
            <li>List $POGEX on various CEX.</li>
            <li>Regular Buyback & Burn Events to increase value of $POGEX</li>
            <li>Partnerships with other big Crypto projects which will be listed on PogeX CEX</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="tokenomics" id="two">
      <h2 :style="{ color: textColor }">Our Tokenomics</h2>
      <div class="token_wrap">
        <div class="left2">
          <img src="../assets/8.png">
        </div>
        <div class="right2">
          <div class="tax">
            <img src="../assets/9.png">
            <h4>3/3 % ,
              <span> BUY/ SELL TAX</span>
            </h4>
          </div>
          <div class="development">
            <img src="../assets/10.png">
            <h4>
              2% ,
              <span>
                MARKETING/ DEVELOPMENT
              </span>
            </h4>
          </div>
          <div class="lp">
            <img src="../assets/11.png">
            <h4>
              1% ,
              <span>AUTO LP</span>
            </h4>
          </div>
        </div>
      </div>
    </div>
    <footer class="footer">
      <div class="login">
        <a href="#">
          <img src="../assets/login.png">
        </a>
        <p>Our hope is for all the degens in the space to join us make PogeX a reality! Once a Degen, always a Degen!</p>
        <p>PogeX - A memetic World of Possibilities!</p>
        <div class="icon">
          <a target="_blank" href="https://t.me/PogeXerc">
            <img src="../assets/dianb.png">
          </a>
          <a target="_blank" href="https://twitter.com/pogexcoin?s=21&t=OGWZ0WBUiJOQDmfglImMtg">
            <img src="../assets/tt.png">
          </a>
        </div>
      </div>
      <div class="links">
        <h5>Quick Links</h5>
        <ul>
          <li><a href="#one">About</a></li>
          <li><a href="#two">Tokenomics</a></li>
          <li><a href="#three">Roadmap</a></li>
        </ul>
      </div>
      <div class="resources">
        <h5>Resources</h5>
        <ul>
          <li><a href="#">Dextool</a></li>
          <li><a href="#">Etherscan</a></li>
        </ul>
      </div>
      <div class="email">
        <h5>Contact Email</h5>
        <ul>
          <li><a href="mailto:Info@pogex.io">Info@pogex.io</a></li>
        </ul>
      </div>
    </footer>
    <div class="copy_right">
      <hr>
      <p>Copyright © 2023 POGEX. All Rights Reserved</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      colors: ['red', 'blue', 'green', 'orange', 'purple', "pink", "Silver", " Gold", "Brown", ' Gray'],
      currentColorIndex: 0
    }
  }, 
  computed: {
    textColor() {
      return this.colors[this.currentColorIndex];
    }
  }, 
  methods:{
    add(){
      main()
    }
  },
  mounted() {
    setInterval(() => {
      this.currentColorIndex = (this.currentColorIndex + 1) % this.colors.length;
    }, 1000);
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@font-face {
  font-family: 'one';
  src: url('../assets/one.woff2') format('woff2'),
}

@font-face {
  font-family: 'two';
  src: url('../assets/two.ttf') format('woff2'),
}

@font-face {
  font-family: 'three';
  src: url('../assets/three.woff2') format('woff2'),
}

@font-face {
  font-family: 'four';
  src: url('../assets/four.woff2') format('woff2'),
}

.box {
  display: flex;
  flex-direction: column;
  align-items: center;
  background: url('../assets/bj_1.png')no-repeat;
  background-position: top center;
  background-size: cover;
  height: 80vw;
  width: 100%;
  position: relative;
}

.head {
  position: relative;
  top: 4vw;
  width: 70%;
  margin: 0 auto;
}

.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  border-radius: 20px;
  background: rgba(255, 255, 255, 0.43);
  padding: 1.5vw 3vw;
  font-family: four;
}

.ul1 {
  display: flex;
  align-items: center;
  gap: 6vw;
}

.ul1>li>a {
  color: rgba(0, 0, 0, 0.60);
  font-size: 1.2vw;
  font-style: normal;
  font-weight: 400;
  line-height: 26px;
}

.ul2 {
  display: flex;
  align-items: center;
  gap: 6vw;
}

.ul2>li>a {
  color: rgba(0, 0, 0, 0.60);
  font-size: 1.2vw;
  font-style: normal;
  font-weight: 400;
  line-height: 26px;
}

.log {
  position: relative;
}

.log>a {
  text-decoration: none;
  cursor: pointer;
}

.log>a>img {
  width: 9vw;
  position: absolute;
  top: -4.2vw;
  left: -4vw;
}

.h1 {
  width: 40vw;
  margin-top: 14vw;
  animation: zoomInDown 2s cubic-bezier(0.77, 0, 0.175, 1) 1;
}

@keyframes zoomInDown {
  0% {
    opacity: 0;
    -webkit-transform: scale3d(0.1, 0.1, 0.1) translate3d(0, -1000px, 0);
    animation-timing-function: cubic-bezier(0.55, 0.055, 0.675, 0.19);
  }

  60% {
    transform: scale3d(0.475, 0.475, 0.475) translate3d(0, 60px, 0);
    animation-timing-function: cubic-bezier(0.175, 0.885, 0.32, 1);
  }
}

.dog {
  width: 45%;
  margin-right: 11vw;
  margin-top: -6.5vw;
  z-index: 1;
}

.dog_house {
  width: 26vw;
  position: absolute;
  top: 50vw;
  left: 57vw;
  z-index: 0;
}

.coin {
  width: 18vw;
  position: absolute;
  top: 59vw;
  left: 21vw;
  z-index: 1;
}

.social_links {
  position: absolute;
  right: 4vw;
  top: 20vw;
  display: flex;
  flex-direction: column;
  gap: 0.5vw;
}

.social_links>a>img {
  width: 3.5vw;
  transition: all .3s;
}

.luse {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  justify-content: space-between;
  padding: 35vw 15vw 5vw 15vw;
  background: url('../assets/bj_2.png')no-repeat;
  background-size: cover;
  background-position: top center;
  position: relative;
  z-index: 2;
  margin-top: -23vw;
}

.left {
  width: 60%;
}

.left>h2 {
  margin-bottom: 1.5vw;
  text-shadow: 0px 4px 26px rgba(64, 251, 18, 0.70), 0px 7px 10px rgba(0, 0, 0, 0.35);
  font-family: two;
  font-size: 2.37vw;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  -webkit-text-stroke: 2px;
}

.left>p {
  font-family: four;
  margin-bottom: 1.5vw;
  color: #fff;
  font-style: normal;
  font-weight: 400;
  line-height: 1.8vw;
  font-size: 1.2vw;
}

.right {
  width: 35%;
}

.right>img {
  width: 80%;
  margin-top: -5vw;
}

.about_2 {
  background: #01C073;
  padding: 5vw 15vw;
  padding-bottom: 20vw;
}

.about2_wrap {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 2vw;
  padding: 3vw;
  border-radius: 2vw;
  border: 17px solid #FFF;
  background: url('../assets/gzuan.png')no-repeat, #098B57;
  background-size: 90%;
  background-position: center;
  margin-top: -25vw;
  position: relative;
  z-index: 3;
}

.left1 {
  width: 25%;
}

.left1>img {
  width: 100%;
}

.right1 {
  width: 72%;
}

.right1 {
  font-family: four;
  color: white;
  font-size: 1.2vw;
  font-style: normal;
  font-weight: 400;
  line-height: 1.8vw;
  /* 136.842% */
}

.roadmap {
  background: url('../assets/bj_3.png')no-repeat;
  background-position: top center;
  background-size: cover;
  position: relative;
  margin-top: -10vw;
}

.social_links>a>img:hover {
  transform: translateX(-10px);
}

.icon>a>img:hover {
  transform: translatey(-10px);
}

.roadmap>img {
  width: 100%;
  margin-top: 6vw;
}

.road_wrap {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  column-gap: 1vw;
  row-gap: 3vw;
  justify-content: space-between;
  padding: 5vw 15vw 20vw 15vw;
}

.road_box {
  width: 40%;
  border-radius: 11px;
  border: 0.7vw solid #FFF;
  padding: 2vw;
  min-height: 21vw;
}

.road_box>h3 {
  color: #FFF;
  text-shadow: 0px 4px 26px #787101, 0px 7px 10px rgba(0, 0, 0, 0.35);
  font-family: two;
  font-size: 1.81vw;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  -webkit-text-stroke: 2px;
  -webkit-text-stroke-color: #756E00;
  margin-bottom: 1vw;
}

.road_box>ul {
  padding-left: 1vw;
}

.road_box>ul>li {
  color: #FFF;
  font-family: four;
  font-size: 1.1vw;
  font-style: normal;
  font-weight: 400;
  line-height: 2.2vw;
  list-style-type: disc;
}

.tokenomics {
  padding: 10vw 15vw 5vw 15vw;
  background: url('../assets/bj_4.png')no-repeat;
  background-size: cover;
  background-position: top center;
  position: relative;
  margin-top: -12vw;
}

.tokenomics>h2 {
  text-align: center;
  margin-bottom: 1.5vw;
  text-shadow: 0px 4px 26px rgba(64, 251, 18, 0.70), 0px 7px 10px rgba(0, 0, 0, 0.35);
  font-family: two;
  font-size: 2.37vw;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  -webkit-text-stroke: 2px;
  -webkit-text-stroke-color: #005231;
}

.token_wrap {
  margin-top: 5vw;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.left2 {
  width: 48%;
}

.left2>img {
  width: 100%;
}

.right2 {
  width: 48%;
  display: flex;
  flex-direction: column;
  gap: 2vw;
}

.tax {
  border-radius: 11px;
  border: 6px solid #FFF;
  background: url('../assets/gzuan.png')no-repeat, #098B57;
  background-position: center;
  background-size: 90%;
  padding: 1vw 3vw;
  width: 80%;
}

.right2>div>h4 {
  font-family: one;
  color: white;
  color: #FFF;
  font-size: 2.06vw;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  text-transform: uppercase;
}

.right2>div>h4>span {
  font-size: 1.1vw;
  font-weight: 700;
  font-family: three;
}

.development {
  border-radius: 11px;
  border: 6px solid #FFF;
  background: url('../assets/gzuan.png')no-repeat, #098B57;
  background-position: center;
  background-size: 90%;
  padding: 1vw 3vw;
  width: 75%;
  margin-left: 15vw;
}

.lp {
  border-radius: 11px;
  border: 6px solid #FFF;
  background: url('../assets/gzuan.png')no-repeat, #098B57;
  background-position: center;
  background-size: 90%;
  padding: 1vw 3vw;
  width: 80%;
}

.footer {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  padding: 5vw 15vw;
  background: #018d6c;
}

.login {
  width: 35%;
  padding-right: 5vw;
}

.login>a>img {
  width: 8vw;
}

.login>p {
  font-size: .8vw;
  line-height: 1.2vw;
  margin-bottom: 1vw;
  font-family: three;
  color: white;
}

.icon {
  display: flex;
  align-items: center;
  gap: 1vw;
}

.icon>a>img {
  width: 3.5vw;
  transition: all .3s;
}

.links {
  width: 20%;
}

.links>h5 {
  color: #FFF;
  font-family: two;
  font-size: 1.4vw;
  font-style: normal;
  font-weight: 400;
  line-height: 5vw;
}

.links>ul>li>a {
  color: #FFF;
  text-align: center;
  font-family: three;
  font-size: 1.1vw;
  font-style: normal;
  font-weight: 400;
  line-height: 3vw;
  transition: all .3s;
}

.resources>h5 {
  color: #FFF;
  font-family: two;
  font-size: 1.4vw;
  font-style: normal;
  font-weight: 400;
  line-height: 5vw;
}

.resources>ul>li>a {
  color: #FFF;
  text-align: center;
  font-family: three;
  font-size: 1.1vw;
  font-style: normal;
  font-weight: 400;
  line-height: 3vw;
  transition: all .3s;
}

.email>h5 {
  color: #FFF;
  font-family: two;
  font-size: 1.4vw;
  font-style: normal;
  font-weight: 400;
  line-height: 5vw;

}

.email>ul>li>a {
  color: #FFF;
  text-align: center;
  font-family: three;
  font-size: 1.1vw;
  font-style: normal;
  font-weight: 400;
  line-height: 3vw;
  transition: all .3s;
}

.copy_right {
  padding: 2vw 15vw;
  background: #018d6c;
  display: flex;
  flex-direction: column;
  gap: 2vw;
  text-align: center;
}

.copy_right>p {
  color: #FFF;
  font-family: four;
  font-size: 1.2vw;
  font-style: normal;
  // font-weight: 400;
  line-height: 1.8vw;
  /* 136.842% */
}

@media (max-width: 600px) {
  .box {
    display: flex;
    flex-direction: column;
    align-items: center;
    background: url('../assets/bj_1.png')no-repeat;
    background-position: top center;
    background-size: cover;
    height: 80vw;
    width: 100%;
    // position: relative;
  }

  .luse {
    display: flex;
    flex-direction: column;
    align-items: start;
    justify-content: space-between;
    padding: 54vw 15vw 5vw 15vw;
    background: url('../assets/bj_2.png')no-repeat;
    background-size: cover;
    background-position: top center;
    position: relative;
    z-index: 2;
    margin-top: -46vw;
  }

  .luse>.left {
    width: 100%;
    text-align: center;
  }

  .left>.colorHeading {
    margin-top: 3.5vw;
    margin-bottom: 1.5vw;
    text-shadow: 0px 4px 26px rgba(64, 251, 18, 0.70), 0px 7px 10px rgba(0, 0, 0, 0.35);
    font-family: two;
    font-size: 6.37vw;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    -webkit-text-stroke: 2px;
  }

  .left>p {
    font-family: four;
    margin-bottom: 1.5vw;
    color: #fff;
    font-style: normal;
    font-weight: 400;
    line-height: 4.8vw;
    font-size: 1.2vw;
  }

  .right {
    width: 100%;
  }

  .right>img {
    width: 100%;
    margin-top: 1vw;
  }

  .about2_wrap {
    flex-direction: column;
  }

  .right1 {
    width: 100%;
    line-height: 4.8vw;
    text-align: center;
  }

  .left1 {
    width: 60%;
  }

  .road_wrap {
    flex-direction: column;
    row-gap: 5vw;
  }

  .road_box {
    width: 100%;
    border-radius: 11px;
    border: 0.7vw solid #FFF;
    padding: 2vw;
    min-height: 45vw;
  }

  .road_box>h3 {
    font-size: 1.81rem;
    text-align: center;
  }

  .road_box>ul>li {
    color: #FFF;
    font-family: four;
    font-size: 3.1vw;
    font-style: normal;
    font-weight: 400;
    line-height: 5.2vw;
    list-style-type: disc;
  }

  .road_box>ul {
    padding: 0 0 0 3vw;
  }

  .token_wrap {
    flex-direction: column;
  }

  .left2 {
    width: 100%;
  }

  .tokenomics>h2 {
    font-size: 6.37vw;
  }

  .social_links>a>img {
    width: 8.5vw;
  }

  .tokenomics {
    padding: 10vw 10vw 5vw 15vw;
  }

  .development {
    width: 80%;
    margin-left: 0;
  }

  .right2 {
    width: 100%;
    gap: 4vw;
  }

  .right2>div {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 6vw 3vw;
  }

  .right2>div>img {
    width: 20%;
  }

  .footer {
    flex-direction: column-reverse;
    align-items: center;
    text-align: center;


    .login {
      width: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
    }
  }

  .login>p {
    line-height: 4vw;
    font-family: four;
  }

  .icon {
    justify-content: center;
  }

  .login>a>img {
    width: 20vw;
  }

  .icon>a>img {
    width: 8.5vw;
  }

  .links {
    width: 35%;

  }

  .links>h5 {
    line-height: 10vw;
  }

  .resources {
    width: 35%;
  }

  .resources>h5 {
    line-height: 10vw;
  }

  .email {
    width: 100%;
    // width: 35%;   
  }

  .email>h5 {
    line-height: 10vw;
  }
}</style>
