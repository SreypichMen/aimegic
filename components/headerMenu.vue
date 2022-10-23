<template>
    <div class="wrapper"> 
        <v-row style="padding: 20px;">
            <v-col align="start" md="3">
                <div class="d-flex ml-10">
                    <!-- <div><h2 style="color: red">Aime </h2></div> -->
                    <img src="https://cdn-icons-png.flaticon.com/512/2839/2839214.png"></img>
                    <div><h2>GIC</h2></div>
                </div>
                
            </v-col>
            <v-col align="center" md="7">
                <v-row>
                    <v-col align="start" md="2">
                        <v-btn text>
                        <v-icon>mdi-home-outline </v-icon>
                        <h3>Home</h3>

                    </v-btn></v-col>
                    <v-col align="start" md="3">
                        <v-btn text>
                        <v-icon>mdi-newspaper-variant-outline </v-icon>
                        <h3>GIC</h3>

                    </v-btn></v-col>
                   
                    <v-col align="center" md="3">
                        <v-btn text>
                            <v-icon>mdi-account-school-outline</v-icon>
                            <h3>Scholarship</h3>
                        </v-btn>
                    </v-col>
                    <v-col align="end" md="3">
                        <v-btn text>
                            <v-icon> mdi-account-group-outline</v-icon>
                            <h3>Community</h3>
                        </v-btn>
                    </v-col>
                </v-row>
            </v-col>
            <v-col align="end" md="2">
                <v-btn text>
                    <v-icon> mdi-account-circle-outline</v-icon>
                    <h3>SignIn</h3>
                </v-btn>
            </v-col>
        </v-row>
    </div>
</template>
<script>



</script>
<style scoped>
.wrapper{
    background-image: linear-gradient(to right,#c973ff 0%, #aebaf8 100%);
    position: sticky;
}
img{
    height: 35px;
    width: 35px;
}
</style>
