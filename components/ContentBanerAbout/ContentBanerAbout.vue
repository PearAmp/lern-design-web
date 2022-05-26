<template>
<div class="container">
        <v-col cols="12"> 
           <v-row>
                <v-col cols="6">
                <img class="imgCovid" src="https://s.isanook.com/ns/0/rp/r/w728/ya0xa0m1w0/aHR0cHM6Ly9zLmlzYW5vb2suY29tL25zLzAvdWQvMTcxMi84NTYzMjg2LzI4MjY5MDMxNl81NjUxMzI3MDE3NzE3MjVfMjM2LmpwZw==.jpg" alt="">
            </v-col>
            <v-col cols="6" class="pl-10">
                <h3>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum pariatur vero doloremque sapiente ratione voluptas!</h3>
                <p class="cutText">Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur maiores eius voluptatem quibusdam, a doloribus facere hic officia cumque accusantium.</p>
                <p class="readMore">Read More -></p>
            </v-col>
           </v-row>
        </v-col>

        <div class="Footer">
            <v-row class="d-flex justify-center text-center pt-15">
            <v-col cols="12" >
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Illum, nesciunt. Voluptate eligendi ipsam voluptates officia dolorem labore esse doloremque nisi?</p>
            </v-col>
        </v-row>
        </div>
</div>
  
</template>

<script>
export default {
    name: 'ContentBanerAbout'

}
</script>

<style lang="scss" scoped>
.container {
    padding-top: 0;
    max-width: 1320px;
}
.imgCovid {
    width: 100%;
    max-width: 450px;
    height: 250px;
}
.cutText {
    padding-top: 20px;
}
.readMore {
    color: blue;
    padding-top: 20px;
}
.Footer .col-12 {
    background-color: #FAFAFA;
    max-width: 90%;
    padding-top: 20px;
     box-shadow:  0 0 50px #888888;
}
.col-6 {
    padding: 0;
}
@media screen and (max-width: 599px) {
   .imgCovid {
    height: auto;
} 
.cutText {
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 2; /* number of lines to show */
    line-clamp: 2;
    -webkit-box-orient: vertical;
    font-size: 1rem;
}
h3 {
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 3; /* number of lines to show */
    line-clamp: 3;
    -webkit-box-orient: vertical;
    font-size: 1rem;
}
    
}
</style>