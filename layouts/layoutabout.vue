<template>
  <v-app>
    <HeaderBar />
    <ContentAboutHead />
    <div class="container">
      <div class="row">
        <div class="contentbody ">
            <v-col cols="12">
              <ContentAboutPost />
            <ContentBanerAbout />
            <ContentFooterAbout />
            </v-col>
        </div>
        <div class="contentside">
          <v-col cols="12">
            <AboutProfile />
          <AboutHospital />
          <AboutPostcovid />
          </v-col>
        </div>
      </div>
    </div>
  </v-app>
</template>

<script>
import HeaderBar from '/components/HeaderBar/HeaderBar.vue'
export default {
  components: { HeaderBar },
  name: 'layoutabo',
}
</script>
<style lang="scss" scoped>
.container {
  max-width: 1320px;
}
.contentbody {
    display: flex;
  width: 70%;
  height: auto;
}
.contentside {
  width: 30%;
  display: flex;
  height: 200px;
  
}
.col-12 {
  padding: 0;
}
@media only screen and (max-width: 991px) {
  .contentbody {
    width: 100%;
  }
  .contentside {
    width: 100%;
  }
  .d-flex {
    flex-direction: column-reverse;
  }
}
</style>
