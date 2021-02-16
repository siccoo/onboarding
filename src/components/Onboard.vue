<template>
    <section class="onboard">
        <div class=" m-0 p-0">
          <div class="row">
            <div class="col-md-5 onboard-left">
                <a href="/" class="logo-brand">
                  <img :src="require('@/assets/OnLogo.jpeg')"/>
                </a>
                <div class="parent">
                    <ul id="childWrapper">
                      <li>
                        <a href="#"> &nbsp; Trial & Pricing </a>
                      </li>
                      <li>
                        <a href="#"> &nbsp; Payment Method</a>
                      </li>
                      <li>
                        <a href="#"> &nbsp; Get started...</a>
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

.onboard-right {
  padding: 40px
}

.onboard-right h5 {
  font-family: Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 30px;
  color: #444444;
  text-transform: uppercase; 
}
</style>
