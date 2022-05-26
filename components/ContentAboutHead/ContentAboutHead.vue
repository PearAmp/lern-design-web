<template>
  <div class="container">
    <v-row>
      <v-col cols="4" class="imgBg">
        <div class="content">
          <h1>Lorem ipsum dolor sit amet.</h1>
          <div class="textBottom">
            <p>May 15 2022</p>
            <img class="icons" src="@/static/heart.png" alt="" />
          </div>
        </div>
      </v-col>
      <v-col cols="4" class="imgBg">
        <div class="content">
          <h1>Lorem ipsum dolor sit amet.</h1>
          <div class="textBottom">
            <p>May 15 2022</p>
            <img class="icons" src="@/static/heart.png" alt="" />
          </div>
        </div>
      </v-col>
      <v-col cols="4" class="imgBg">
        <div class="content">
          <h1>Lorem ipsum dolor sit amet.</h1>
          <div class="textBottom">
            <p>May 15 2022</p>
            <img class="icons" src="@/static/heart.png" alt="" />
          </div>
        </div>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: 'ContentAboutHead',
}
</script>

<style lang="scss" scoped>
.container {
  max-width: 1320px;
  padding-top: 30px;
}
.imgBg {
  background-image: url('https://www.mhesi.go.th/images/2563/pornnapa/130463/COVID/1.jpg');
  height: 450px;
  position: relative;
}
.content {
  position: absolute;
  bottom: 0;

  color: #fff;
  width: 100%;
  padding: 20px;
  font-size: 0.9rem;
}
.col-4 {
  padding: 0;
}
.icons {
  width: 100%;
  max-width: 20px;
  height: 20px;
}
.textBottom {
  display: flex;
  justify-content: space-between;
}
@media screen and (max-width: 599px) {
  .content {
    font-size: 0.5rem;
  }
  .imgBg {
    height: 250px;
  }

}
</style>
