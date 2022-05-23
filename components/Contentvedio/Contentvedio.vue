<template>
  <div class="container-fluid">
    <div class="container">
      <v-row class="d-flex justify-center">
        <v-col cols="4" md="2">
          <div class="topcontent">
            <p>VEDIO COVID</p>
          </div>
        </v-col>
        <v-col cols="8" md="10">
          <div class="topcontent1">
            <p><i class="arrow right"></i>&nbsp; RECENT NEWS</p>
            <div class="imgarrow">
              <img class="arrowimg" src="@/static/arrow-right.png" alt="" />
              <img class="arrowimg" src="@/static/left.png" alt="" />
            </div>
          </div>
        </v-col>
      </v-row>

      <!-- ========vedio========== -->
      <v-row class="d-flex justify-center">
        <v-col cols="3">
          <iframe class="ifremvedio"
            width="320"
            height="300"
            src="https://www.youtube.com/embed/8Y5TXszdQt8"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
        </v-col>
        <v-col cols="3" class="pl-2">
          <iframe class="ifremvedio"
            width="320"
            height="300"
            src="https://www.youtube.com/embed/8Y5TXszdQt8"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
        </v-col>
        <v-col cols="3" class="pl-3">
          <iframe class="ifremvedio"
            width="320"
            height="300"
            src="https://www.youtube.com/embed/8Y5TXszdQt8"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
        </v-col>
        <v-col cols="3" class="pl-4">
          <iframe class="ifremvedio"
            width="320"
            height="300"
            src="https://www.youtube.com/embed/8Y5TXszdQt8"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Contentvedio',
}
</script>

<style scoped>
* {
  padding: 0;
}
.container-fluid {
  box-sizing: border-box;
  padding-top: 60px;
}
.container {
  max-width: 1320px;
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
  display: flex;
  justify-content: space-between;
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
.arrowimg {
  width: 30px;
  height: 30px;
}
@media screen and (max-width: 599px) {
  .topcontent1 {
    font-size: 1.25rem;
  }
  .topcontent {
    font-size: 1.25rem;
  }
  .ifremvedio {
      width: 120px;
      height: 120px;
  }
}
</style>
