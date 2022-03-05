<template>
  <div class="container" style="padding: 50px 0">
    <div class="row">
      <div class="col">
        <div class="container">
          <div class="row row-cols-2">
       
    
     <div data-aos="fade-right" class="col-12 text-center " > 
       <h2 class="text-primary text-center ">ABOUT ME</h2>
            
            </div>
              <hr />
         
            

            <div class="col-12">
              <div  data-aos="fade-right" class="text-center">
                <img src="../assets/imgy.png" class="img-fluid1" alt="Yassine Azedine" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row" style="">
      <div data-aos="fade-left" class="col-lg-8 col-md-6 col-xd-12 one text-center">
        <h4 class="">WHO AM I?</h4>
        <p class="text-uppercase text-justify">
          <span>
            <div class="container desc text-center ">
            <strong>
            Je suis un jeune développeur Full Stack  à l'écoute des opportunités qui 
             me permettront d'acquérir des nouvelles compétences techniques et qui  
             se révèlera être un atout  pour ma futur  carrière professionnelle 
              .</strong>
             
             </div>
          </span>
        </p>

        <p class="text-uppercase text-justify">
       
        </p>
      </div>

      <div data-aos="fade-left" class="col-lg-4 col-md-6 col-xd-12 text-capitalize">
        <h4 class="text-center"><strong>Yassine Azedine</strong></h4>
        <br />

        <div class="medi">
          <div>
            <p class=""><strong>Email:</strong> Yassine.Azedine0711@gmail.com</p>
          </div>
          <div>
            <p class=""><strong>Phone:</strong> +121 696377875</p>
          </div>
          <div>
            <p class=""><strong>City:</strong>Youssoufia,Maroc</p>
          </div>
          <div>
            <p class=""><strong>Languages:</strong> Francais,Anglais</p>
          </div>
        </div>

        <ul class="text-center">
          <li>
            <a href=" https://www.facebook.com/yassine.azedine.184/">
              <img
                src="https://img.icons8.com/material-sharp/24/000000/facebook-circled--v3.png"
                style="width: 50px"
              />
              </a>
              <a href="https://twitter.com/YassineAzedine">
      <img src="https://img.icons8.com/ios-filled/50/000000/twitter-circled--v1.png"
      
       style="width: 50px"
      />
              </a>
              <a href="https://www.linkedin.com/in/yassine-azedine-1233a5156/">
              <img
                src="https://img.icons8.com/ios-filled/26/000000/linkedin.png"
                style="width: 50px"
              />
              </a>
              <a href="https://github.com/YassineAzedine">
              <img
                src="https://img.icons8.com/ios-glyphs/30/000000/github.png"
                style="width: 50px"
              />
            </a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "description",
};
</script>
<style >
.img-fluid1 {
  width: 30%;
  border-radius: 50%;
   border: 1px solid #ddd;
     padding: 5px;
       border: 1px solid #ddd;
 
  padding: 5px;

}

.desc{
   text-indent: 50px;
  text-align: justify;
  letter-spacing: 3px;
   border-bottom:1px dotted;
  margin-left:auto;
  margin-right:auto;
  text-align:center;
  border-bottom:1px dotted;
  margin-left:auto;
  margin-right:auto;
  text-align:center;
  width: 100px;
    text-shadow: 1px 1px;
    text-shadow: 1px 1px red;
}
span {
  color: 
  #7b79fd;
}
ul {
  list-style: none;
}
hr {
  border: 1px solid;
  width: 30%;
}
hr{
    border: solid;
    width: 40%;
    color:white
}

@media only screen and (max-width: 600px) {

  .medi {
    margin-left: 20%;
   
  }
  .desc{
    
    
text-align: center;
  }
}
</style>