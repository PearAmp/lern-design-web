<template>
  <div class="container">
    <h2>COVID-19 POST</h2>
    <div class="contantPost pt-5">
      <v-row class="d-flex justify-center" v-for="n in 4" :key="n">
        <v-col cols="6" md="6">
          <img
            class="covidImg"
            src="https://www.paho.org/sites/default/files/styles/flexslider_full/public/banner-covid-19-1280x549.jpg?h=0f7a3278&itok=nrTaMkjD"
            alt=""
          />
        </v-col>
        <v-col cols="6" md="6">
          <p>Lorem ipsum dolor sit amet</p>
          <div class="textDate">
            <p>
              <img class="icons" src="@/static/calendar.png" alt="" /><span
                >May 3 2022</span
              >
            </p>
          </div>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutPostcovid',
}
</script>

<style lang="scss" scoped>
.covidImg {
  width: 100%;
  max-width: 200px;
  height: auto;
}
.icons {
  width: 100%;
  max-width: 20px;
}
.textDate {
  position: relative;
}
span {
  position: absolute;
  padding-left: 10px;
}
@media screen and (max-width: 991px) {
  .covidImg {
    width: 100%;
    max-width: 400px;
    height: auto;
  }
}
</style>
