<template>
  <div class="container">
    <div class="contact">
      <h2>Send us a message</h2>
      <h3 class="pt-3">Send us a message and we'll respond within 24 hours.</h3>

      <div class="emailInput pt-10">
        <v-row class="d-flex justify-center">
          <v-col cols="6" md="6">
            <div class="form">
              <label for="fullName">Full Name</label>
              <v-spacer></v-spacer>
              <input
                type="text"
                id="fullName"
                name="fullName"
                placeholder="write your full name"
              />
            </div>
          </v-col>
          <v-col cols="6" md="6">
            <div class="form">
              <label for="email">E-Mail</label>
              <v-spacer></v-spacer>
              <input
                type="text"
                id="email"
                name="email"
                placeholder="write your email........"
              />
            </div>
          </v-col>
        </v-row>
      </div>

      <div class="emailInput pt-10">
        <v-row class="d-flex justify-center">
          <v-col cols="6" md="6">
            <div class="form">
              <label for="telephone">Telephone</label>
              <v-spacer></v-spacer>
              <input
                type="text"
                id="telephone"
                name="telephone"
                placeholder="Phone number"
              />
            </div>
          </v-col>
          <v-col cols="6" md="6">
            <div class="form">
              <label for="organize">Organisation</label>
              <v-spacer></v-spacer>
              <input
                type="text"
                id="organize"
                name="organize"
                placeholder="Organisation Name"
              />
            </div>
          </v-col>
        </v-row>
      </div>

      <v-row>
        <div class="extraInput">
          <label for="subject">Subject</label>
          <textarea
            id="subject"
            name="subject"
            placeholder="Write something.."
            style="height: 200px"
          ></textarea>
        </div>
      </v-row>

   <div class="submit">
          <v-btn color="success" width="130">
      Submit
    </v-btn>
   </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContentContact',
}
</script>

<style lang="scss" scoped>
.container {
  max-width: 1320px;
  padding-top: 20px;
}
.contact {
  background-color: #eeeeee;
  height: auto;
  padding: 80px;
}
h3 {
    font-weight: 300;
}
input {
  border: 1px solid #b0bec5;
  width: 80%;
}

.logo {
  width: 100%;
  max-width: 150px;
  height: 150px;
  border-radius: 50%;
}
input[type='text'],
select,
textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  resize: vertical;
}

.extraInput {
  width: 100%;
  padding-top: 30px;
  margin: 10px;
}
.submit {
    padding-top: 20px;
    display: flex;
    justify-content: right;
}
@media screen and (max-width: 599px) {
   .contact {
       padding: 20px;
   } 
    
}
</style>
