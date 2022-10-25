<template>
<div class="poster">
    <v-img width="100% " height="550px" src="https://img.freepik.com/free-vector/watercolor-stains-abstract-background_23-2149107181.jpg?w=996&t=st=1666673729~exp=1666674329~hmac=f309e46ea8d3f3bfa314322ba01923f3908c79c9a8266fa6ec86a8284f66853c">
        <v-row class="lightbox white--text pa-2 fill-height" style=" background-color: rgba(0, 0, 0, 0);height:560px;align-content: center; ">           
            <v-col  align="start" style="margin-top: 200px; margin-left: 100px" >
              <div class="text ">
               <div class="text1"><i><h1 style="color:  #4481eb;; font-weight: bold; font-size: 2.5em">Find out what good for your study</h1></i></div>
               <div style="border-bottom: 4px solid green"></div>
               <div><h3  style="color: black;font-weight: bold; font-size: 1.2em; margin-top: 20px">Information, Opportunities and Our Community are here for you!</h3></div>
              </div>
             </v-col>
             <v-col align="end" class="mt-14" >
                <img style="padding: 20px" height="420px" src="~/assets/img/poster_img.png"></img>
             </v-col>
         </v-row>
        
    </v-img>
    <br></br>
    <v-container>
    <div class="card_box"> 
    <v-row class="card-container" > 
        <v-col  >
            <v-card class="card">
                <v-img height="230px" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT394sek2I9SOLeV3c52Mt6ZgxyxUs72zsXgRa6sWRM84Iv6qWMmQHaX2xDuphFpxqk-6E&usqp=CAU">
                   <div class="d-flex">
                    <div> <img class="image" height="75px" width="75px" src="https://cdn-icons-png.flaticon.com/512/3233/3233180.png"></img></div>
                    <div><h2 style="padding: 10px; margin-top: 30px; color: blue; font-size: 1.2em">Detail Information of GIC </h2> </div>
                </div>
                <div style=" text-align: center">
                    <h3>We provide information about GIC department and what you want to know about GIC </h3>
                </div>
                </v-img>
            </v-card>
        </v-col>
        <v-col >
            <v-card class="card">
                <v-img height="230px" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTQftB-tjkz9z3T0MX1nTQutGHExSnlwyGhQreKNqB_OQtD9moxPxm0YuYagkGQR-dapRM&usqp=CAU">
                    <div class="d-flex">
                        <div> <img class="image" height="75px" width="75px" src="https://cdn-icons-png.flaticon.com/512/5605/5605075.png"></img></div>
                        <div><h2 style="padding: 10px; margin-top: 30px; color: red; font-size: 1.2em">Opportunities </h2> </div>
                    </div>
                    
                   
                    <v-row></v-row>
                   
              
            </v-img>
            </v-card>
        </v-col>
        <v-col>
            <v-card  class="card">
                <v-img height="230px" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTknbRGToLjj_a29Q01mcKztP4fP3pQ0Ua2PKYlLJfaP0QStXwZqmYJeeii-3bnCGh8JQM&usqp=CAU">
                    <div class="d-flex">
                        <div> <img class="image" height="75px" width="75px" src="https://cdn-icons-png.flaticon.com/512/5612/5612654.png"></img></div>
                        <div><h2 style="padding: 10px; margin-top: 30px; color: green; font-size: 1.2em">GIC Student Community</h2> </div>
                    </div>
                   
            </v-img>
            </v-card>
        </v-col>
    </v-row>
   </div>
</v-container>
</div>
</template>
<script>

</script>
<style scoped>
.poster{
    width: 100%;height: 500px;
    position: relative;
    /*background-image: linear-gradient(to top, #4481eb 0%, #04befe 100%);*/
}
.card_box{
 
    display: flex;
    justify-content: center;
 
    position: absolute;
    top: 430px;
}

.card{
    border: 1px solid white;
    height: auto;
    width: 390px;

}
.image{
    margin-left: 20px;
    margin-top: 20px;
}

  
</style>