<template>
  <div class="container-fluid">
    <div class="Ontop"></div>
    <div class="container">
      <v-row>
        <v-col cols="12">
          <h3>BREAKINGNEWS</h3>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="8">
          <v-row>
            <v-col cols="5">
              <img
                class="ImgUk"
                src="https://cdnuploads.aa.com.tr/uploads/Contents/2020/03/31/thumbs_b_c_f0c9e70408e03dcbd2c231d82228c08b.jpg?v=210121"
                alt=""
              />
            </v-col>
            <v-col cols="7">
              <p>
                Lorem ipsum dolor sit amet consectetur.
                <span class="colortext">lorem</span>
              </p>
            </v-col>
          </v-row>
        </v-col>
        <v-col cols="4">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum,
            quas?
          </p>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Contentbreaknews',
}
</script>

<style scoped>
.container {
  max-width: 1320px;
  padding: 0;
}
.Ontop {
  padding-top: 30px;
}
.col-8 {
  border: 1px solid;
}
.col-4 {
  border: 1px solid;
}
.col-12 h3 {
  color: #ffff;
  background-color: red;
  padding-left: 10px;
}
.colortext {
  color: red;
  font-weight: bold;
}
.col-7 p {
  padding-top: 40px;
}
.col-12 {
  padding: 0;
}
.col-4 p {
  padding-top: 30px;
}

.ImgUk {
  width: 180px;
  height: auto;
}
@media screen and (max-width: 599px) {
  .ImgUk {
    width: 100px;
    height: auto;
  }
  .col-7 p {
    padding-top: 10px;
  }
  .col-8 {
    padding-top: 50px;
  }
}
</style>
