<template>
  <div class="section">
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">HUMANS OF NEW YORK</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarText" style="padding-left: 700px;">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">STORIES</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">COUNTRIES</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">SERIES</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">SHARE</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
    <div class="img1">
      <h4 style="color: white;"> HUMANS OF NEW YORK</h4> 
      <h1 style="font-size: 120px; font-family: 'Times New Roman', Times, serif;"><strong>Series</strong> </h1>
      <p> These stories focus on specific populations examining <br> their experiences and the challenges that they face</p>
    </div>
    <div class="img2">
    <div class="igm2">
      <h4 style="color: white;">HUMANS OF NEW YORK</h4>  
    </div>
     <p style="font-size: 110px; color:chocolate; font-family: 'Times New Roman',Times,serif;">Invisible Wounds</p>
     <button type="button" class="btn btn-outline-dark btn-lg" style="color: white; border: solid black">READ SERIES</button>
    </div>

    <div class="img3">
    <h4 style="color: white;"> HUMANS OF NEW YORK</h4>
    
    <p style="font-size: 110px; color:red; font-family: 'Times New Roman',Times,serif;">Pediatric Cancer</p>
     <button type="button" class="btn btn-outline-dark btn-lg" style="color: white; border: solid black">READ SERIES</button>
    </div>

    <div class="img4" >
    <h4 style="color: white;"> HUMANS OF NEW YORK</h4>
     <p style="font-size: 110px; color:rgb(203, 240, 222); font-family: 'Times New Roman',Times,serif;">Inmate Stories</p>
     <button type="button" class="btn btn-outline-dark btn-lg" style="color: white; border: solid black">READ SERIES</button>
    </div>
    <div class="img5">
    <h4 style="color: white;"> HUMANS OF NEW YORK</h4>
    <p style="font-size: 110px; color:orange; font-family: 'Times New Roman',Times,serif;">Syrian Americans</p>
     <button type="button" class="btn btn-outline-dark btn-lg" style="color: white; border: solid black">READ SERIES</button>
    </div>
     <div class="img6">
    <h4 style="color: white;"> HUMANS OF NEW YORK</h4>
    
    <p style="font-size: 110px; color:white; font-family: 'Times New Roman',Times,serif;">Refugee Stories</p>
     <button type="button" class="btn btn-outline-dark btn-lg" style="color: white; border: solid black">READ SERIES</button>
    </div>
    <div class="cadre">
      <img src="@/assets/ImagesNet/black.png" alt="">
      
    <p style="font-size: 150px; color:white; font-family: 'Times New Roman',Times,serif;">More Humans of New York</p>
    <div class="social">
    <img src="@/assets/ImagesNet/face.png">
    <img src="@/assets/ImagesNet/twitter.png">
    <img src="@/assets/ImagesNet/face.png">
  </div>
    </div> 
  </div>
</template>

<style>
.nav{
  background-color : light;
}

.nav-link:hover{
  color: red;
}
.nav-item{
  list-style: outside;
  padding: 0px 20px;
}
.nav-item:hover{
  color: red !important;
}
.navbar-brand{
  border: solid black;
}

.img1{
  background: light;
  height: 400px;
  font-size: 110px;
  font-family: 'Times New Roman', Times, serif;
}
.img2{
  background-image: url("@/assets/ImagesNet/img2.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position-x: 100%;
  background-position-y: 14%;
  padding: 15px;
  position: relative;
  margin: 0px;
  text-align: center;
  height: 500px;
  padding-top: 80px;
  box-sizing: border-box;

  color: chocolate;
}
.img3{
  background-image: url("@/assets/ImagesNet/img3.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position-x: 100%;
  background-position-y: 14%;
  padding: 15px;
  position: relative;
  margin: 0px;
  text-align: center;
  height: 500px;
  padding-top: 80px;
  box-sizing: border-box;
  color: red;    
}
  .img4{
  background-image: url("@/assets/ImagesNet/img4.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position-x: 100%;
  background-position-y: 14%;
  padding: 15px;
  position: relative;
  margin: 0px;
  text-align: center;
  height: 500px;
  padding-top: 80px;
  box-sizing: border-box;
  color: aquamarine;

}
  .img5{
  background-image: url("@/assets/ImagesNet/img5.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position-x: 100%;
  background-position-y: 14%;
  padding: 15px;
  position: relative;
  margin: 0px;
  text-align: center;
  height: 500px;
  padding-top: 80px;
  box-sizing: border-box;
  color: orange;
}
  
  .img6{
  background-image: url("@/assets/ImagesNet/img6.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position-x: 100%;
  background-position-y: 14%;
  padding: 15px;
  position: relative;
  margin: 0px;
  text-align: center;
  height: 500px;
  padding-top: 80px;
  box-sizing: border-box;
  color: white;    
}
.section{
  text-align: center;
}
.cadre{
  background-color: black;
  height: 500px;
  font-size: 80px;
  font-family: 'Times New Roman', Times, serif;
}
.social{
  gap: 10%;
}







</style>

<footer>

</footer>
