<template>
  <div class="container-fluid">
    <div class="container">
      <div class="contentbody">
        <v-row>
          <v-col cols="7" class="content1">
            <div class="Topcontent">
              <h2>HIGH SEASON</h2>
            </div>

            <v-carousel hide-delimiters height="auto">
              <v-carousel-item
                v-for="(item, i) in items"
                :key="i"
                :src="item.src"
              ></v-carousel-item>
            </v-carousel>
          </v-col>

          <v-col cols="5" class="content2">
            <v-row>
              <v-col cols="12" class="d-flex justify-center">
                <img
                  class="Imagecontent1"
                  src="https://www.sikarin.com/wp-content/uploads/2021/06/14272288860600.jpg"
                  alt=""
                />
              </v-col>
            </v-row>
            <v-row class="mt-4">
              <v-col cols="6" class="d-flex justify-center">
                <img
                  class="ImageCovid"
                  src="https://www.bpl.co.th/pweb/images/COVID-19.png"
                  alt=""
                />

                <div class="textcontent1">
                  <p>COVID-19</p>
                </div>
              </v-col>
              <v-col cols="6" class="d-flex justify-center">
                <img
                  class="ImageCovid"
                  src="https://static.thairath.co.th/media/4DQpjUtzLUwmJZZO8zyqukM1yaVTPmVzZxTEllHO2Ofv.jpg"
                  alt=""
                />
              </v-col>
            </v-row>
          </v-col>
        </v-row>
      </div>

      <!-- ============ Mobile ============== -->
      <div class="contentbody2">
        <v-row>
          <v-col cols="12" class="content1">
            <v-carousel hide-delimiters height="auto">
              <v-carousel-item
                v-for="(item, i) in items"
                :key="i"
                :src="item.src"
              ></v-carousel-item>
            </v-carousel>
          </v-col>

          <v-col cols="12" class="content2">
            <v-row>
              <v-col cols="12" class="d-flex justify-center">
                <img
                  class="Imagecontent1"
                  src="https://www.sikarin.com/wp-content/uploads/2021/06/14272288860600.jpg"
                  alt=""
                />
              </v-col>
            </v-row>
            <v-row class="mt-4">
              <v-col cols="6" class="d-flex justify-center">
                <img
                  class="ImageCovid"
                  src="https://www.bpl.co.th/pweb/images/COVID-19.png"
                  alt=""
                />

                <div class="textcontent1">
                  <p>COVID-19</p>
                </div>
              </v-col>
              <v-col cols="6" class="d-flex justify-center">
                <img
                  class="ImageCovid"
                  src="https://static.thairath.co.th/media/4DQpjUtzLUwmJZZO8zyqukM1yaVTPmVzZxTEllHO2Ofv.jpg"
                  alt=""
                />
              </v-col>
            </v-row>
          </v-col>
        </v-row>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContentImageNews',
  data() {
    return {
      items: [
        {
          src: 'https://positioningmag.com/wp-content/uploads/2020/03/%E0%B8%95%E0%B9%89%E0%B8%AD%E0%B8%87%E0%B8%A3%E0%B8%AD%E0%B8%94Covid19.jpg',
        },
        {
          src: 'https://digitalbusinessconsult.asia/wp-content/uploads/2020/03/DBC-COVID-19-01.png',
        },
        {
          src: 'https://storage.googleapis.com/techsauce-prod/ugc/uploads/2020/3/Coronavirus_Map_2.jpg',
        },
        {
          src: 'https://live.staticflickr.com/65535/52074204503_f90fbd9584_o_d.png',
        },
      ],
    }
  },
}
</script>

<style scoped>
* {
  box-sizing: border-box;
}
.contentbody2 {
  display: none;
}
.container {
  max-width: 1320px;
  height: 600px;
}
.content1 {
  overflow: hidden;
  position: relative;
}
.content2 {
  position: relative;
}
.Imagecontent1 {
  width: 600px;
  overflow: hidden;
}
.ImageCovid {
  width: 250px;
  overflow: hidden;
}
.col-7 {
  padding: 15px;
}
.col-12 {
  padding: 15px;
}
.col-6 {
  height: auto;
  padding: 0;
}
.textcontent1 {
  position: absolute;
  bottom: 8px;
  text-align: center;
  background-color: #fafafa;
  -webkit-mask-image: linear-gradient(black, transparent);
  width: 30%;
}
.Topcontent {
  position: absolute;
  z-index: 999;
  background: red;
}
@media screen and (max-width: 599px) {
  .container-fluid {
    height: 750px;
  }
  .contentbody {
    display: none;
  }
  .contentbody2 {
    display: block;
  }
  .col-6 {
    padding: 15px;
    height: 150px;
  }
}
</style>
