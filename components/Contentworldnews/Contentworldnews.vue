<template>
  <div class="container">
    <v-row class="d-flex justify-center">
      <v-col cols="4" md="2">
        <div class="topcontent">
          <p>WORLD NEWS</p>
        </div>
      </v-col>
      <v-col cols="8" md="10">
        <div class="topcontent1">
          <p><i class="arrow right"></i>&nbsp; WATCH THE WORLD NEWS</p>
        </div>
      </v-col>
    </v-row>
    <div class="space"></div>
    <!-- ===========conten 2 =============== -->
    <v-row class="d-flex justify-center">
      <v-col cols="12" md="6">
        <v-row>
          <v-col cols="6" md="6">
            <img
              class="covidvc"
              src="https://ti-health.org/wp-content/uploads/2020/11/coronavirus-covid-19-vaccine-equitable-distribution.jpg"
              alt=""
            />
          </v-col>
          <v-col cols="6" md="6">
            <div class="textunderline">
              <h2>Germany</h2>
            </div>
            <div class="textp">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure
                sunt fugiat molestiae, autem est impedit?
              </p>
            </div>
            <div class="textp2">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure
                sunt fugiat molestiae, autem est impedit?
              </p>
              <div class="textdayago">
                <p>2 dey ago</p>
              </div>
            </div>
          </v-col>
        </v-row>
      </v-col>
      <v-col cols="12" md="6" class="contentimg2">
        <v-row class="d-flex justify-center">
          <v-col cols="6" md="6">
            <img
              class="covidvc"
              src="https://m.economictimes.com/thumb/msid-80228460,width-1200,height-900,resizemode-4,imgsize-141492/covid-19-vaccine-afp1.jpg"
              alt=""
            />
          </v-col>
          <v-col cols="6" md="6" class="contenttext2">
            <div class="textunderline">
              <h2>America</h2>
            </div>
            <div class="textp">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure
                sunt fugiat molestiae, autem est impedit?
              </p>
            </div>
            <div class="textp2">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure
                sunt fugiat molestiae, autem est impedit?
              </p>
              <div class="textdayago">
                <p>20 dey ago</p>
              </div>
            </div>
          </v-col>
        </v-row>
      </v-col>
    </v-row>

    <!-- ===========conten 3 =============== -->
    <div class="space"></div>
    <v-row class="d-flex justify-center">
      <v-col cols="12" md="6">
        <v-row>
          <v-col cols="6" md="6">
            <img
              class="covidvc"
              src="https://s3.amazonaws.com/cms.ipressroom.com/338/files/20208/5f7364cb2cfac20c4ad7790f_flu+shot+man/flu+shot+man_hero.jpg"
              alt=""
            />
          </v-col>
          <v-col cols="6" md="6">
            <div class="textunderline">
              <h2>Jpan</h2>
            </div>
            <div class="textp">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure
                sunt fugiat molestiae, autem est impedit?
              </p>
            </div>
            <div class="textp2">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure
                sunt fugiat molestiae, autem est impedit?
              </p>
              <div class="textdayago">
                <p>4 dey ago</p>
              </div>
            </div>
          </v-col>
        </v-row>
      </v-col>
      <v-col cols="12" md="6" class="contentimg2">
        <v-row class="d-flex justify-center">
          <v-col cols="6" md="6">
            <img
              class="covidvc"
              src="https://gdb.voanews.com/922E2FCB-6177-4B9D-BB3F-478513561A3B_w1200_r1.jpg"
              alt=""
            />
          </v-col>
          <v-col cols="6" md="6" class="contenttext2">
            <div class="textunderline">
              <h2>France</h2>
            </div>
            <div class="textp">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure
                sunt fugiat molestiae, autem est impedit?
              </p>
            </div>
            <div class="textp2">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure
                sunt fugiat molestiae, autem est impedit?
              </p>
              <div class="textdayago">
                <p>9 dey ago</p>
              </div>
            </div>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: 'Contentworldnews',
}
</script>

<style scoped>
* {
  padding: 0;
}

.container {
  max-width: 1320px;
  box-sizing: border-box;
  padding-top: 50px;

}
.arrow {
  border: solid black;
  border-width: 0 4px 4px 0;
  display: inline-block;
  padding: 4px;
}

.right {
  transform: rotate(-45deg);
  -webkit-transform: rotate(-45deg);
}
.topcontent {
  font-size: 1.5rem;
  background-color: red;
  color: #ffff;
  font-weight: bold;
  text-align: center;
}
.topcontent1 {
  font-size: 1.5rem;
  padding-left: 10px;
}
.covidvc {
  width: 330px;
  height: 220px;
  padding-top: 12px;
  padding-left: 10px;
}
.covidvc1 {
  width: 330px;
  height: 230px;
}
.space {
  padding-top: 40px;
}
.textunderline {
  -webkit-text-decoration-line: underline;
  text-decoration-line: underline;
  text-decoration: underline solid red 40%;
  border-bottom: 1px solid #cfd8dc;
  display: flex;
  justify-content: left;
}
.textp {
  border-bottom: 2px solid #cfd8dc;
  padding-top: 10px;
  padding-bottom: 0;
}
.contentimg2 {
  padding-left: 25px;
}
.contenttext2 {
  padding-left: 10px;
}
.textdayago {
  display: flex;
  justify-content: right;
  font-size: 0.8rem;
  line-height: 0;
  font-weight: 500;
  padding-right: 20px;
}

@media screen and (max-width: 599px) {
  .covidvc {
    width: 270px;
    height: 200px;
  }
  .textdayago {
    padding-right: 30px;
  }
  .contentimg2 {
    padding-left: 0;
  }
  .contenttext2 {
    padding-left: 0;
  }
  .textp {
    font-size: 0.9rem;
  }
  .textp2 {
    font-size: 0.9rem;
  }
  .textunderline {
      font-size: 0.9rem;
  }
  .topcontent1 {
      font-size: 1.25rem;
  }
  .topcontent {
      font-size: 1.25rem;
  }
}
</style>
