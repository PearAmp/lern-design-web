<template>
  <div class="container-fluid">
    <div class="container">
      <v-row class="d-flex justify-center">
        <v-col cols="4" md="2">
          <div class="topcontent">
            <p>NATIONAL NEWS</p>
          </div>
        </v-col>
        <v-col cols="8" md="10">
          <div class="topcontent1">
            <p><i class="arrow right"></i>&nbsp; LATEST NEWS IN DETAILS</p>
          </div>
        </v-col>
      </v-row>
      <div class="space"></div>
      <v-row>
        <v-col cols="12" md="9">
          <v-row>
            <v-col cols="6" md="5">
              <img
                class="covidvc"
                src="https://cloudfront-us-east-2.images.arcpublishing.com/reuters/RAX34RTZZ5PWXMSULCJQ2XH6JE.jpg"
                alt=""
              />
            </v-col>
            <v-col cols="6" md="7">
              <div class="textcontent">
                <h3>
                  Lorem ih3sum dolor sit, amet consectetur adipisicing elit.
                </h3>
                <h3>Lorem ih3sum dolor sit, amet</h3>
                <!-- <p>Lorem ipsum dolor sit amet.</p> -->
              </div>
              <div class="contenttextp">
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem
                  omnis asperiores natus tenetur incidunt blanditiis?
                </p>
              </div>
              <div class="contenttextp1">
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem
                  omnis asperiores natus tenetur incidunt blanditiis?
                </p>
              </div>
            </v-col>
          </v-row>
          <v-row class="contentspace">
            <v-col cols="6" md="5">
              <img
                class="covidvc"
                src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b0/Moderna_COVID-19_vaccine.jpg/800px-Moderna_COVID-19_vaccine.jpg"
                alt=""
              />
            </v-col>
            <v-col cols="6" md="7">
              <div class="textcontent">
                <h3>
                  Lorem ih3sum dolor sit, amet consectetur adipisicing elit.
                </h3>
                <h3>Lorem ih3sum dolor sit, amet</h3>
                <!-- <p>Lorem ipsum dolor sit amet.</p> -->
              </div>
              <div class="contenttextp">
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem
                  omnis asperiores natus tenetur incidunt blanditiis?
                </p>
              </div>
              <div class="contenttextp1">
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem
                  omnis asperiores natus tenetur incidunt blanditiis?
                </p>
              </div>
            </v-col>
          </v-row>
          <v-row class="contentspace">
            <v-col cols="6" md="5">
              <img
                class="covidvc"
                src="https://media.komchadluek.net/uploads/images/md/2022/02/M6M7Txo47meXvSawuPM4.webp?x-image-process=style/LG"
                alt=""
              />
            </v-col>
            <v-col cols="6" md="7">
              <div class="textcontent">
                <h3>
                  Lorem ih3sum dolor sit, amet consectetur adipisicing elit.
                </h3>
                <h3>Lorem ih3sum dolor sit, amet</h3>
                <!-- <p>Lorem ipsum dolor sit amet.</p> -->
              </div>
              <div class="contenttextp">
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem
                  omnis asperiores natus tenetur incidunt blanditiis?
                </p>
              </div>
              <div class="contenttextp1">
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem
                  omnis asperiores natus tenetur incidunt blanditiis?
                </p>
              </div>
            </v-col>
          </v-row>
        </v-col>
        <v-col cols="12" md="3" class="contenmedailast">
          <v-row class="d-flex justify-center">
            <v-col cols="12">
              <img
                class="imgcontent"
                src="https://tna.mcot.net/wp-content/uploads/2021/06/1545190-e1622612637663-1536x806-1.jpg"
                alt=""
              />
            </v-col>
          </v-row>
          <div class="space"></div>
          <v-row class="text">
            <v-col cols="12" class="texth3">
              <h3>LATEST NEWS</h3>
            </v-col>
          </v-row>
          <v-row class="textcolor" v-for="n in 5" :key="n">
            <v-col cols="6" md="5">
              <img
                class="imgsmall"
                src="https://news.yale.edu/sites/default/files/styles/featured_media/public/vaccination-campaign.jpg?itok=5zUYvkSF&c=a75e254fe1da31f2732f6b0d7bce1413"
                alt=""
              />
            </v-col>
            <v-col cols="6" md="7">
              <div class="textlastnews">
                <h4>Lorem, ipsum dolor.</h4>
                <p>Lorem ipsum dolor sit amet consectetur.</p>
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
  name: 'Contentnational',
}
</script>

<style scoped>
* {
  padding: 0;
}
.container-fluid {
  max-width: 100%;
  padding-top: 50px;
}
.container {
  max-width: 1320px;
  box-sizing: border-box;
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
  width: calc(100% - 20px);
  height: 200px;
  padding-left: 10px;
}

.contenttextp {
  border-bottom: 2px solid #cfd8dc;
  padding-top: 10px;
  word-wrap: break-word;
}
.space {
  padding-top: 50px;
}
.contentspace {
  padding-top: 20px;
}
.imgcontent {
  width: 360px;
  height: 250px;
  padding-left: 12px;
  padding-top: 12px;
  padding-right: 12px;
}
.texth3 {
  padding-left: 10px;
  background-color: red;
  color: #ffff;
}
.text {
  padding-left: 12px;
  padding-right: 12px;
}
.textcolor {
  margin-left: 0;
  margin-right: 0;
  background-color: #424242;
}
.imgsmall {
  width: 140px;
  height: 60px;
  padding: 5px;
}
.textlastnews {
  color: #ffff;
}
.textlastnews p {
  line-height: 1;
  font-size: 0.8rem;
}
@media screen and (max-width: 599px) {
  .topcontent1 {
    font-size: 1.25rem;
  }
  .topcontent {
    font-size: 1.25rem;
  }
  .contenttextp {
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 2;
    line-clamp: 2;
    -webkit-box-orient: vertical;
  }
  .textcontent {
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 2;
    line-clamp: 2;
    -webkit-box-orient: vertical;
  }
  .contenttextp1 {
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 2;
    line-clamp: 2;
    -webkit-box-orient: vertical;
  }
  .contenmedailast {
      padding-top: 30px;
  }
  .imgcontent {
      display: none;
  }
  .imgsmall {
  width: 250px;
  height: 100px;
}
.textlastnews {
    padding-top: 20px;
}
.texth3 {
    padding-left: 20px;
    font-size: 1.25rem;
}
}
@media screen and (max-width: 991px) {
     .imgcontent {
      display: none;
  }
    
}
</style>
