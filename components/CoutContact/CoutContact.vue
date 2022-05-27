<template>
<div class="container">
    <div class="header text-center">
        <v-row >
            <v-col cols="12">
<h1>THE DETAILS</h1>
        <hr />
        <p class="text">Loremipsum dolor sit amet consectetur adipisicing elit. Autem minima at minus est dolorum officiis accusamus earum repellendus delectus debitis.</p>

        <div class="text-left pl-5 content">
            <p>e. weot@gmail.com</p>
        <p>p. 0995678843</p>
        <p>w. www.theemail.com</p>
        </div>

        <div class="get text-left pl-5 pt-5">
            <h3>GET IN TOUCH</h3>
             <p>E. weot@gmail.com</p>
              <p>P. 0995678843</p>
              <v-row class="pt-4">
                  <img class="icons" src="@/static/facebook-icon.png" alt="">
                  <img class="icons" src="@/static/twitter.png" alt="">
                  <img class="icons" src="@/static/instagram.png" alt="">
              </v-row>
        </div>

        <div class="get text-left pl-5 pt-10">
            <h3>LATEST TWEET</h3>
              <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quod, nam.</p>
        </div>
            </v-col>
        </v-row>
    </div>
</div>
  
</template>

<script>
export default {
    name: 'CoutContact'

}
</script>

<style lang="scss" scoped>
hr {
  color: black;
  width: 50%;
  margin-left: 25%;
  
 
}
.text {
    text-align: justify;
  text-justify: inter-word;
  padding: 20px;
}
.content {
    line-height: 1;
}
.icons {
    width: 100%;
    max-width: 40px;
    padding-left: 10px;
}
h3 {
    padding-bottom: 10px;
}
.get p {
    line-height: 1;
}
</style>