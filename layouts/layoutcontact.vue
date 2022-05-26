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
        <div class="contact"></div>
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
}

.contactform {
  width: 70%;
  display: flex;
}
.contact {
  width: 30%;
  background-color: aqua;
  height: 200px;
  display: flex;
}
@media only screen and (max-width: 991px) {
  .contactform {
    width: 100%;
  }
  .contact {
    width: 100%;
  }
  .d-flex {
    flex-direction: column-reverse;
  }
}
</style>
