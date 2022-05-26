<template>
<div class="container">
    <div class="emailInput">
        <v-row class="d-flex justify-center">
        <input type="text" id="fname" name="fname" placeholder="write your email........">
        <img class="icons" src="@/static/fast-forward.png" alt="">
    </v-row>
    </div>

    <div class="profile pt-10">
        <v-row >
            <v-col cols="12" class="d-flex justify-center">
        <img class="logo" src="https://s.isanook.com/ga/0/rp/r/w850/ya0xa0m1w0/aHR0cHM6Ly9zLmlzYW5vb2suY29tL2dhLzAvdWQvMjExLzEwNTY5Mzcvd2hvKDEpLnBuZw==.png" alt="">

            </v-col>
            <v-col cols="12" class="d-flex justify-center">
                <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque voluptates possimus quos provident, dicta dolorum aperiam qui tempore quam voluptatum cupiditate sed odio temporibus incidunt illum nisi. Alias, quasi quas!</p>

            </v-col>
        </v-row>
    </div>
</div>
  
</template>

<script>
export default {
    name: 'AboutProfile'

}
</script>

<style lang="scss" scoped>
.container {
    padding-top: 75px;
    
}
input {
    border: 1px solid #B0BEC5;
    width: 80%;
}
.icons {
    width: 50px;
    background-color: blue;
}
.logo {
    width: 100%;
    max-width: 150px;
    height: 150px;
    border-radius: 50%;
}
.profile {
    border-bottom: 1px solid #B0BEC5;
}
</style>