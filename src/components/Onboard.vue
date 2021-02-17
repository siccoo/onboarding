<template>
    <section class="onboard">
        <div class="">
          <div class="row">
            <div class="col-md-5 onboard-left">
                <a href="/" class="logo-brand">
                  <img :src="require('@/assets/OnLogo.jpeg')"/>
                </a>
                <div class="parent">
                    <ul class="wrapper">
                      <li>
                        <a href="#" class="link"> &nbsp; Trial & Pricing &nbsp; -> </a>
                      </li>
                      <li>
                        <a href="#" class="link"> &nbsp; Payment Method</a>
                      </li>
                      <li>
                        <a href="#" class="link"> &nbsp; Get started...</a>
                      </li>
                    </ul>
                </div>
                <div class="parent2">
                    <p>Success is not final; failure is not fatal; it is the courage to continue that counts.</p>
                    <h6>-Winston Churchill</h6>
                </div>
            </div>
            <div class="col-md-7 onboard-right">
                <h5>Hey, Terry</h5>
                <div class="row">
                  <div class="col-md-6 left-box">
                    <h2>Start your <span>30 days</span> Trial</h2>
                    <p>Select your preferred package below</p>
                  </div>
                  <div class="col-md-6 right-box">
                    <p class="ng">ngn</p>
                    <p class="numb">1,999,999</p>
                    <p class="total">Total <small>(Excludes VAT)</small></p>
                  </div>
                    <div class="col-md-6">          
                      <div class="border-white">
                        <p>Starts From <span class="ng">NGN</span></p>

                      </div>
                    </div>
                    <div class="col-md-6">

                    </div>
                </div>
            </div>
          </div>
          
        </div>
    </section>
</template>

<script>
export default {
  data () {

    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans&family=Noto+Serif&family=Roboto&display=swap');

.onboard {
  min-height: 100vh;
  overflow: hidden;
}

.onboard-left {
  background: #050505;
  background-size: cover;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
}

.onboard-left .wrapper {
  list-style-type: none;
  padding: 20px;
  margin: 50px;
}

.wrapper .link {
    font-family: "Roboto";
    font-style: normal;
    font-weight: bolder;
    font-size: 20px;
    line-height: 47px;
    letter-spacing: 0.051em;
    color: #d5d5d5;
    list-style: none;
    text-decoration: none !important;
}

@media only screen and (max-width: 1024px) {
  .wrapper .link {
    font-size: 15px;
    line-height: 38px;
  }
}

.wrapper .link:hover {
  border-left: 2px solid #ffd700;
  color: #fff;
}

.onboard-right {
  padding: 40px
}

.onboard-right h5 {
  font-family: "Roboto" sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 30px;
  color: #a9a9a9;
  text-transform: uppercase; 
}

@media only screen and (max-width: 1024px){
  .onboard-right h5 {
    font-size: 12px;
    line-height: 20px;
  }
}

.onboard-right h2 {
  font-family: 'Roboto', serif;
  font-style: normal;
  font-weight: bold;
  font-size: 30px;
  line-height: 45px;
  letter-spacing: 0.797236px;
}

@media only screen and (max-width: 1024px){
  .onboard-right h2 {
    font-size: 20px;
    line-height: 30px;
  }
}

.onboard-right span {
  color: #ffd700;
  font-style: italic;
  font-weight: normal;
}

.onboard-right p {
  font-family: "Roboto" sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 25px;
  color: #a9a9a9;
}

@media only screen and (max-width: 1024px){
  .onboard-right p {
    font-size: 12px;
    line-height: 16px;
  }
}

.onboard-right .right-box {
  margin-top: -10px;
}

.onboard-right .ng {
  font-family: "Roboto" sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 30px;
  color: #0000ff;
  text-transform: uppercase;
  margin: 0;
}

.onboard-right .numb {
  font-family: "Roboto" sans-serif;
  font-style: normal;
  font-weight: bolder;
  font-size: 20px;
  line-height: 30px;
  color: #0000ff;
  margin: 0;
}

.onboard-right .total {
  font-family: "Roboto" sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 14px;
  line-height: 25px;
  color: #a9a9a9;
}

.onboard-right small {
  text-transform: uppercase;
  font-weight: normal;
}
</style>
