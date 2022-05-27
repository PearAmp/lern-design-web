<template>
  <v-app>
    <HeaderBar />
    <div class="container">
      <v-row>
        <div class="contactform">
          <v-col cols="12">
            <ContentContact />
          </v-col>
        </div>
        <div class="contact">
          <v-row>
            <v-col cols="12">
              <CoutContact />
            </v-col>
          </v-row>
        </div>
      </v-row>
    </div>
  </v-app>
</template>

<script>
import HeaderBar from '/components/HeaderBar/HeaderBar.vue'
export default {
  components: { HeaderBar },
  name: 'layoutcontact',
}
</script>

<style lang="scss" scoped>
.container {
  max-width: 1320px;
  padding-top: 30px;
}

.contactform {
  width: 70%;
  display: flex;
  border-right: 1px solid #000;
}
.contact {
  width: 30%;
  background-color: #eeee;
  height: auto;
  display: flex;
}
.col-12 {
  padding: 0;
}
@media only screen and (max-width: 991px) {
  .contactform {
    width: 100%;
      border-right: none;

  }
  .contact {
    width: 100%;
  }
  .d-flex {
    flex-direction: column-reverse;
  }
}
</style>
