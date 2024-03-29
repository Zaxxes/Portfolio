<template>
  <div class="nav">
    <v-app-bar app color="grey-lighten-3" dark flat class="px-8">
      <v-btn icon>
        <v-icon color="#57BDE2">fas fa-home</v-icon>
      </v-btn>
      <v-spacer></v-spacer>
      <center>
      <v-btn text @click="scroll('home')">Home</v-btn>
      <v-btn text @click="scroll('project')">Project</v-btn>
      <v-btn text @click="scroll('about')">About</v-btn>
      <v-btn text @click="scroll('contact')">Contact</v-btn>
    </center>
    </v-app-bar>
  </div>
  </template>
  
  <script>
  export default {
    name: 'NavbarComponent',

    methods: {
      scroll(refName) {
        const element = document.getElementById(refName);
        element.scrollIntoView({behavior: "smooth"});
      }
    }
    
  }
  </script>
  
  <style>
 .nav {
  
 }
  </style>
  