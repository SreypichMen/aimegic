<template>
    <nav v-scroll="handleScroll" >
    <div id="box1" class="wrapper"> 
        <v-row style="padding: 20px;">
            <v-col align="start" md="3">
                 <nuxt-link to="/" style="text-decoration:none;"></nuxt-link>
                <div class="d-flex ml-10">
                   
                    <img src="https://cdn-icons-png.flaticon.com/512/2839/2839214.png"></img>
                    <div><h2>GIC</h2></div>
                  
                </div>
                  </nuxt-link>
            </v-col>
            <v-col align="center" md="7">
                <v-row>
                    <v-col align="start" md="2">
                        <v-btn text to="/">
                        <v-icon class="icon">mdi-home-outline </v-icon>
                        <h3>Home</h3>

                    </v-btn></v-col>
                    <v-col align="start" md="2">
                        <v-btn text>
                        <v-icon class="icon">mdi-newspaper-variant-outline </v-icon>
                        <h3>GIC</h3>

                    </v-btn></v-col>
                   
                    <v-col align="center" md="3">
                        <v-btn text>
                            <v-icon class="icon">mdi-account-school-outline</v-icon>
                            <h3>Scholarship</h3>
                        </v-btn>
                    </v-col>
                    <v-col align="end" md="3">
                        <v-btn text>
                            <v-icon class="icon"> mdi-account-group-outline</v-icon>
                            <h3>Community</h3>
                        </v-btn>
                    </v-col>
                </v-row>
            </v-col>
            <v-col align="end" md="2">
                <v-btn text>
                    <v-icon class="icon"> mdi-account-circle-outline</v-icon>
                    <h3>SignIn</h3>
                </v-btn>
            </v-col>
        </v-row>
    </div>
    </nav>
</template>
<script>
 export default {
      data () {
        return {
          
        }
      },
       methods: {
        handleScroll: function (evt, el) {
          var box1 = document.getElementById('box1')
            if (window.scrollY <80) {
                box1.classList.remove('box1');
        }
        else {
          box1.classList.add('box1');
        }
      
      }
  
    
    }}


</script>
<style scoped>
.wrapper{
    /*background-image: linear-gradient(to right,#c973ff 0%, #aebaf8 100%);/*
   
  
    /* position: sticky; */ 
    background-color: transparent;
    position: fixed;
    top:0;
    scroll-behavior: smooth;
    z-index: 10000;
    width:100%;
    height: 70px;
 
    box-shadow: 6px 4px 5px #0003;
}
img{
    height: 35px;
    width: 35px;
}

.box1{
    

    color: white !important;
    background-color: blue;
}
.v-btn--active {
    
  
   
    color: blue!important;
    
   
    transition:0.1s all;
   
    font-weight: bold;
  }
  
</style>
