<template>
  <v-parallax
    dark
    src="https://cdn.vuetifyjs.com/images/parallax/material2.jpg"
    style="border-radius: 30px; "
  >
    <br><br>
    <h2 class="h2-1">
      Sing up your bank account
    </h2>
    <div>
      <v-text-field
        label="Your name"
        hide-details="auto"
        solo
        placeholder="Your name"
        background-color="transparent"
      />
      <v-text-field
        label="Bank Account"
        hide-details="auto"
        solo
        placeholder="Bank Account"
        background-color="transparent"
      />
      <v-text-field
        label="Mobile phone number"
        hide-details="auto"
        solo
        placeholder="Mobile phone number"
        background-color="transparent"
      />
      <v-text-field
        label="Email"
        hide-details="auto"
        solo
        placeholder="Email"
        background-color="transparent"
      />
      <v-text-field
        label="Password"
        hide-details="auto"
        solo
        placeholder="Password"
        background-color="transparent"
      />
    </div><br>
    <h4>Use 6 characters with a mix of numbers and letters</h4><br>

    <v-row>
      <v-col class="d-flex justify-center ">
        <v-btn class="btn1" color="yellow ">
          <span style="color: rgb(0, 0, 0)">SIGN UP</span>
        </v-btn> &nbsp; &nbsp; &nbsp;
        <h3>or</h3> &nbsp; &nbsp; &nbsp;
        <v-btn class="btn2" color="dark">
          <span>CANCEL</span>
        </v-btn>
      </v-col>
    </v-row>
    <h4>Already Signed up?</h4><p style="color:blue-grey darken-2">
      Login
    </p>
  </v-parallax>
</template>
<style>
.h2-1{
  margin: 5px;
}

</style>
