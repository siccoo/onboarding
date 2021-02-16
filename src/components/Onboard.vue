<template>
    <section class="onboard">
        <div class=" m-0 p-0">
          <div class="row">
            <div class="col-md-4 onboard-left">
                <a href="/" class="logo-brand">
                  <img :src="require('@/assets/OnLogo.jpeg')"/>
                </a>
            </div>
            <div class="col-md-8 onboard-right">

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
  background: #111111;
  background-size: cover;
  
}
</style>
