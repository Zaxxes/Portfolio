<template>
  <v-app id="home" :style="{ background: $vuetify.theme.themes.dark.background}">
    <NavbarComponent />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="berns.png" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="6">
          <h2 class="white--text text-darken-8 top">Hi I'm Bernie</h2>
         <marquee behavior="" direction="right"> <h1 class="grey--text">Web Designer</h1> </marquee>
          <p class="grey--text">
             I am good at Visual arts and currently studied many popular <br>
             application for Graphic and Web Design.
          </p>
          <v-btn tile color="#2596be" dark>about me</v-btn>
        </v-col>
        <v-col cols="12" class="padd">
          <div class="first" id="project">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#2596be" x-large class="ml-3">
                    mdi-account-box-outline
                  </v-icon>
                  <h3 class="white--text ml-3mt-4">Student</h3>
                  <p class="grey--text ml-3 mt-6">
                  <strong>  Bachelor of Science and <br> Information Technology </strong>
                  </p>
                  
                </div>
                <div class="child bgColor2">
                  <v-icon x-large class="ml-3" dark>mdi-folder-image</v-icon>
                  <h3 class="white--text ml-3 mt-4">APPS-DEV Project</h3>
                  <p class="black--text ml-3 mt-6">
                   <strong> ACGOWC System </strong> <br> (Front End Designer)
                  </p>
                  <v-btn dark text>
                    Click Here
                    <v-icon right>mdi-open-in-new</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor1">
                  <v-icon color="#57BDE2" x-large class="ml-3">mdi-book-open-page-variant</v-icon>
                  <h3 class="white--text ml-3 mt-4">Creative Web Design</h3>
                  <p class="grey--text ml-3 mt-6">
                     Below are the List of sample <br> project created
                  </p>
                  <v-btn color="#57BDE2" dark text>
                    Click Here
                    <v-icon right>mdi-open-in-new</v-icon>
                  </v-btn>
                </div>
              </v-col>
              <v-col cols="12" class="mt-10">
                <div class="child1">
                  <h1 class="light-blue--text text-darken-4 mt-4 number">3rd</h1>
                <strong>  <h3 class="grey--text mt-4"> Year</h3> </strong>
                </div>
                <div class="child2 mRight">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="light-blue--text text--darken-4"> Capstone</h1>
                        <p class="grey--text">On going</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h4 class="light-blue--text text--darken-4">Title Defense</h4>
                        <p class="grey--text">Barangay Profiling System</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
                <div class="child2 ">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="light-blue--text text--darken-4"> Portfolio</h1>
                        <p class="grey--text">Online Vue js Portfolio</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h4 class="light-blue--text text--darken-4">Personal</h4>
                        <p class="grey--text">Achievements</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col md="3" offset-md="3" id="about">
          <h4 class="light-blue--text">Achievements</h4>
          <p class="grey--text"> Below is my Certificate and Achievements</p>
        </v-col>
        <v-col md="3" class="text-end">
          <v-btn tile color="#57BDE2" dark>View All</v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card class="pa-2 py-12" outlined tile width="250px" height="250px" color="#1e1e1e">
            <v-img src="achievements.png " contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card class="pa-2 py-12" outlined tile width="250px" height="250px" color="#1e1e1e">
            <v-img src="achievements1.png" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="#57BDE2" dark text class="ml-n4">
            Creative Web Design
          </v-btn> <br />
          <v-btn color="grey" dark text class="ml-n4">
            Organized by CCA
          </v-btn>
        </v-col>
        <v-col md="3" >
          <v-btn color="#57BDE2" dark text class="ml-n4">
            Best Stance Speaker
          </v-btn> <br />
          <v-btn color="grey" dark text class="ml-n4">
            Organized by ISYL
          </v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card class="pa-2 py-12" outlined tile width="250px" height="250px" color="#1e1e1e">
            <v-img src="achievements2.png " contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card class="pa-2 py-12" outlined tile width="250px" height="240px" color="#1e1e1e">
            <v-img src="achievements3.jpg" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="#57BDE2" dark text class="ml-n4">
            Digital Literacy
          </v-btn> <br />
          <v-btn color="grey" dark text class="ml-n4">
            Organized by FUNDLIFE
          </v-btn>
        </v-col>
        <v-col md="3" >
          <v-btn color="#57BDE2" dark text class="ml-n4">
            International Summit of Young Leaders
          </v-btn> <br />
          <v-btn color="grey" dark text class="ml-n4">
            Organized by ISYL
          </v-btn>
          <br><br> 
          <br><br>
        </v-col><v-col cols="12" class="padd topInverse">
          <div class="second">
            <div class="secondchild1" id="contact">
            <v-row>
              <v-col cols="8">
                <h1 class="white--text">
                  You can contact & message me  <br>through the platforms below
                </h1>
                
              </v-col>
              <v-col cols="4">
                <v-btn tile color="#57BDE2" dark class="mt16">Contact</v-btn>
              </v-col>
              </v-row>
          </div>
          </div>
        <v-col cols="12" class="padd topInverse">
          <div class="second">
            <div class="secondchild1" id="contact">
            <v-row>
              <v-col cols="8">
                <h1 class="white--text">
                  You can contact & message me  <br>through the platforms below
                </h1>
                
              </v-col>
              <v-col cols="4">
                <v-btn tile color="#57BDE2" dark class="mt16">Contact</v-btn>
              </v-col>
              </v-row>
          </div>
          </div>
          <v-toolbar class="topTolbar" color="grey-lighten-3" dark flat>
            <div style="position: absolute; margin-left: auto; margin-right: auto; left: 0; right: 0; text-align: caenter">
            <v-btn text>Home</v-btn>
            <v-btn text>Project</v-btn>
            <v-btn text>About</v-btn>
            <v-btn text>Contact</v-btn>
            </div>
          </v-toolbar>
        </v-col>
      </v-row>
    </v-container>
    <FooterComponent />
  </v-app>
  
</template>

<script>
  import NavbarComponent from '../components/NavbarComponent.vue';
  import FooterComponent from '../components/FooterComponent.vue';

  export default {
    name: 'HomeView',

    components: {
      NavbarComponent,
      FooterComponent
    },
  }
</script>

<style scoped>



.top{
  margin-top: 180px;
}

.topInverse{
  margin-top: -100px;
}

.topTolbar {
  margin-top: 50px;
  text-align: center
}

.first {
  width: 100%;
  height: 610px;
  background: #043a4e;
  text-align: center;
  padding: 2rem 2rem
}

.second {
  width: 100%;
  height: 120%;
  background: #181818;
  text-align: center;
  padding: 2rem 2rem
}

.secondchild1 {
  display: inline-block;
  background-color: #1e1e1e;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 150px;
}

.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px
}

.bgColor1 {
  background-color: #1e1e1e;
}

.bgColor2 {
  background-color: #2596be;
}

.child1{
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;  
}

.child2{
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}

.mRight {
  margin-right: 8px;
}

.mButton {
  margin-top: 8px;
}

.padding {
  padding: 8px 0px ;
}

.col-12.padd {
  padding: 12px 0 !important;
}

.col-12.childcol {
  background: #043a4e;
  padding: 0 !important;
}

h1.number {
  font-size: 50px;
  font-weight: bold;
}
</style>