<template>
  <div class="container">
    <div class="footContent">
      <v-row>
        <v-col cols="12" md="6">
          <h2>Lorem ipsum dolor sit.</h2>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quia error
            molestias ad. Quam accusamus quisquam repellat eveniet ut neque est.
          </p>

          <div class="botton">
            <v-btn color="red">
              <h4>Read More</h4>
            </v-btn>
          </div>
        </v-col>

        <v-col cols="12" md="6">
          <h2>Lorem ipsum dolor sit.</h2>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quia error
            molestias ad. Quam accusamus quisquam repellat eveniet ut neque est.
          </p>

          <div class="botton">
            <v-btn color="red">
              <h4>Read More</h4>
            </v-btn>
          </div>
        </v-col>
      </v-row>

      <div class="contentImage pt-15">
        <v-col cols="12">
          <v-row>
            <v-col cols="6">
              <h3>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                Sapiente, veniam.
              </h3>
              <p class="text">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. Porro,
                quod accusamus quisquam reprehenderit iusto culpa perferendis
                eaque iure magni. Culpa.
              </p>
              <p class="readmore">Read More -></p>
            </v-col>
            <v-col cols="6">
              <img
                class="footerImg"
                src="https://www.vejthani.com/wp-content/uploads/2020/04/COVID-19-COVID-19-TH-00.jpg"
                alt=""
              />
            </v-col>
          </v-row>
        </v-col>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContentFooterAbout',
}
</script>

<style lang="scss" scoped>
.container {
  padding-top: 80px;
}
h4 {
  color: #ffff;
}
p {
  padding-top: 15px;
}
.footerImg {
  width: 100%;
  max-width: 400px;
  height: 200px;
}
.readmore {
  color: blue;
}
@media screen and (max-width: 599px) {
  .botton {
    display: flex;
    justify-content: center;
  }
  .footerImg {
    height: auto;
  }
  h3 {
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 1; /* number of lines to show */
    line-clamp: 1;
    -webkit-box-orient: vertical;
    font-size: 1rem;
  }
  .text {
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 5; /* number of lines to show */
    line-clamp: 5;
    -webkit-box-orient: vertical;
    font-size: 1rem;
  }
}
</style>
