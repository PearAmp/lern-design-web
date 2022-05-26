<template>
  <div class="container">
    <v-row>
      <v-col cols="12" class="d-flex justify-center">
        <img
          class="imgBg"
          src="https://www.mhesi.go.th/images/2563/pornnapa/130463/COVID/1.jpg"
          alt=""
        />
        <div class="content">
          <h1>
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Vero,
            nesciunt molestiae. A, possimus dolorum. Porro?
          </h1>
          <div class="textBottom">
            <p>May 15 2022</p>
            <img class="icons" src="@/static/heart.png" alt="" />
          </div>
        </div>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12">
        <v-col cols="6"></v-col>
        <v-col cols="6"></v-col>
      </v-col>
    </v-row>
    <v-row></v-row>
  </div>
</template>

<script>
export default {
  name: 'ContentAboutPost',
}
</script>

<style lang="scss" scoped>
.container {
  width: 100%;
  position: relative;
}
h1 {
  font-size: 1.5rem;
}
.imgBg {
  padding-top: 50px;
  width: 100%;
  height: 400px;
}
.content {
  position: absolute;
  bottom: 0;
  color: #fff;
  width: 100%;
  padding: 20px;
  font-size: 0.9rem;
  padding-bottom: 70px;
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
  .imgBg {
    height: 250px;
  }
  h1 {
    font-size: 1rem;
  }
}
</style>
