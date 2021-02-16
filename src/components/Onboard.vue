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
                        
                      </li>
                    </ul>
                </div>
            </div>
            <div class="col-md-7 onboard-right">

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
</style>
