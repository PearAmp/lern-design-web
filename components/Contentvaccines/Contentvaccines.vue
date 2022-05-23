<template>
  <div class="container-fluid">
    <div class="container">
      <v-row class="d-flex justify-center">
        <v-col cols="12" md="5">
          <img
            class="vaccineimg"
            src="https://www.vejthani.com/wp-content/uploads/2021/05/Side-effects-Covid-19-vaccine-ENG1.jpg"
            alt=""
          />
        </v-col>
        <v-col cols="12" md="7">
          <v-row class="d-flex justify-center">
            <v-col cols="6" md="4">
              <img
                class="vaccineimg1"
                src="https://www.paho.org/sites/default/files/styles/max_1500x1500/public/2021-02/covid-19-vaccine-virus-bk-1500-871.jpg?itok=NJGPfWM1"
                alt=""
              />
            </v-col>
            <v-col cols="6" md="8">
              <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                Voluptatem velit possimus eum quas culpa vel.
              </p>
              <div class="textbottom">
                <p>2 day ago 25/Mey/2022</p>
              </div>
            </v-col>
          </v-row>
          <v-row class="d-flex justify-center">
            <v-col cols="6" md="4">
              <img
                class="vaccineimg1"
                src="https://www.paho.org/sites/default/files/styles/max_1500x1500/public/2021-02/covid-19-vaccine-virus-bk-1500-871.jpg?itok=NJGPfWM1"
                alt=""
              />
            </v-col>
            <v-col cols="6" md="8">
              <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                Voluptatem velit possimus eum quas culpa vel.
              </p>
              <div class="textbottom">
                <p>2 day ago 25/Mey/2022</p>
              </div>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Contentvaccines',
}
</script>

<style scoped>
.container-fluid {
  max-width: 100%;
  padding-top: 30px;
}
.container {
  max-width: 1320px;
  padding: 0;
  box-sizing: border-box;
}
.vaccineimg {
  width: 560px;
  height: 250px;
  padding-top: 12px;
}
.vaccineimg1 {
  width: 250px;
  height: 100px;
}
.col-md-5 {
  padding: 0;
}
.textbottom {
  line-height: 2rem;
}
@media screen and (max-width: 559px) {
  .vaccineimg1 {
    width: 250px;
    height: 150px;
  }
}
</style>
