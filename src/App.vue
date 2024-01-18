<template>
  <div class="card">
  <div class="navigation">
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">HUMAINS OF<br> NEW YORK</br></a>
    <div class="collapse navbar-collapse" id="navbarText" style="padding-left: 700px;">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link" href="#"> STORIES</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"> COUNTRIES</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"> SERIES</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"> SHARE</a>
        </li>
      </ul>
      
    </div>
  </div>
</nav>
  </div>
  <div class="paragraphe">
      <h5 style="font-size: 25px;">HUMANS OF NEW YORK</h5>
          <div class="title">
            <h1 style="font-family:'Times New Roman', Times, serif; font-size: 100px;">Series</h1>
            <p style="font-family: 'Times New Roman', Times, serif; font-size: 30px;">These stories focus on specific populations, examining <br>their experiences and the challenges that they face.</p>
          </div>
         
  </div>
    <div class="img1">
     <div class="ecriture1">
      <h8><strong>HUMANS OF NEW YORK</strong></h8>
    <p style="font-size: 110px; color: rgb(76, 27, 27); font-family: 'Times New Roman', Times, serif;">Invisible<br>Wounds</p>
    <button type="button" class="btn btn-outline-dark btn-lg">READ SERIES</button>
     </div>
    </div>
    
    <div class="img2">
      <div class="ecriture2">
        <h8><strong>HUMANS OF NEW YORK</strong></h8>
      <p style="font-size: 110px;  color: brown; font-family: 'Times New Roman', Times, serif;">Pediatric<br>Cancer</p>
      <button type="button" class="btn btn-outline-dark btn-lg">READ SERIES</button>

      </div>
    </div>
   
    <div class="img3">
      <div class="ecriture3">
        <h8><strong>HUMANS OF NEW YORK</strong></h8>
    <p style="font-size: 110px; color:rgb(145, 172, 145); font-family: 'Times New Roman', Times, serif;">Inmate<br>Stories</p>
      <button type="button" class="btn btn-outline-dark btn-lg">READ SERIES</button>
      </div>
    </div>
    <div class="img4">
      <div class="ecriture4">
        <h8><strong>HUMANS OF NEW YORK</strong></h8>
    <p style="font-size: 110px; color:rgb(199, 91, 28); font-family: 'Times New Roman', Times, serif;">Syrian<br>Americans</p>
    <button type="button" class="btn btn-outline-dark btn-lg">READ SERIES</button>
      </div>
    </div>
    <div class="img5">
      <div class="ecriture5">
        <h8><strong>HUMANS OF NEW YORK</strong></h8>
      <p style="font-size: 100px; color:black; font-family: 'Times New Roman', Times, serif;">Refugee<br>Stories</p>
      <button type="button" class="btn btn-outline-dark btn-lg">READ SERIES</button>
      </div>
    </div>
  </div>
  <div style="width: 1700px; height: 250px;  background-color: black;" class="cardfooter">
   
  <h1 style="color: white;">More Humans of New York</h1>
  <img src="@/assets/ImagesNet/Face1.png" alt="" class="icons">
  <img src="@/assets/ImagesNet/social.png" alt="" class="icons">
  <img src="@/assets/ImagesNet/social1.png" alt="" class="icons">
</div>
<div class="footer">
 <ul style="width: auto;">
        <li class="item">
          <a class="link" href="#"> STORIES</a>
        </li>
        <li class="item">
          <a class="link" href="#"> COUNTRIES</a>
        </li>
        <li class="item">
          <a class="link" href="#"> SERIES</a>
        </li>
        <li class="item">
          <a class="link" href="#"> SHARE</a>
        </li>
       <li class="item">
          <a class="link" href="#"> ABOUT</a>
        </li>
        <div  style="color: aliceblue; background-color:blue; width: 100px; height: 30px;" class="card-follows">
          <p style=""><img style="width: 25px; height: 25px;"  src="@/assets/ImagesNet/social.png" alt="" class="icons">FOLLOWS</p>
         
        </div>
        <p style="font-size: small; width: auto;">17M people are following this.Be the first of your friends to<br>following</p> 
         <a style="text-align: center; font-size: small; width: auto; margin-left: 300px;" class="nav-link" href="#"> NEW YORK <br>TIMES N°1 BEST<br>SELLER</a>
   </ul>  
</div>

</template>
<style>
.nav-link:hover{
  color: red !important;
}
.nav-item{
  list-style: outside;
  padding: 0px 20px;
}
.nav-item:hover{
  color: red !important;
}
  .navbar-brand{
    border: solid black 1px;
    width: 133px;
    height: 70px;
    font-size: x-small;
  }
  .navigation{
    border-bottom: solid black 1px;
    
  }
  
  .paragraphe{
    margin-top: 30px;
    text-align: center;
  }
  
  .img1{
    background-image: url("@/assets/ImagesNet/Image1.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position-x: 100% ;
    background-position-y: 30%;
    padding: 15px;
    position: relative;
    margin: 0px;
    text-align: center;
    height: 550px;
    padding-top: 80px;
    box-sizing: border-box;
   
  }

 .ecriture1{
  margin-left: 700px;
 }
  .btn{
    border: solid black 1px;
   border-radius: 0px;
    
  }
  
  .img2{
    background-image:url("@/assets/ImagesNet/Image2.jpg") ;
    background-repeat: no-repeat;
    background-size: cover;
    background-position-x: 100% ;
    background-position-y: 14%;
    padding: 15px;
    position: relative;
    margin: 0px;
    text-align: center;
    height: 550px;
    padding-top: 80px;
    box-sizing: border-box;
  }
  .ecriture2{
    margin-right: 830px;
  }
  .img3{
    background-image: url("@/assets/ImagesNet/Image3.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position-x: 100% ;
    background-position-y:20%;
    padding: 15px;
    position: relative;
    margin: 0px;
    text-align: center;
    height: 600px;
    padding-top: 80px;
    box-sizing: border-box;
  }
  .ecriture3{
    margin-left: 700px;
  }
  .img4{
    background-image: url("@/assets/ImagesNet/Image4.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position-x: 100% ;
    background-position-y: 20%;
    padding: 15px;
    position: relative;
    margin: 0px;
    text-align: center;
    height: 550px;
    padding-top: 80px;
    box-sizing: border-box;
    
  }
  .ecriture4{
    margin-right: 800px;
  }
  .img5{
    background-image:url("@/assets/ImagesNet/Image5.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position-x: 100% ;
    background-position-y: 18%;
    padding: 15px;
    position: relative;
    margin: 0px;
    text-align: center;
    height: 550px;
    padding-top: 80px;
 }
 .ecriture5{
  margin-left: 900px;
 }
 .card{
  width: 1500px;
  height: 450px;
  margin: 0px;

 
 }
 
 .cardfooter{
  margin: 0px;
  margin-top:0px;
  text-align: center;
  height: 50px;
   
 }
 .icons{
  width: 50px;
  height: 50px;
 
 }
 ul{
  display: flex;
 }
 .link{
  text-decoration: none;
  color: black;
  font-size: large;
 }
 

 .link:hover{
  color: red !important;
}
.item{
  list-style: outside;
  padding: 0px 20px;
}
.item:hover{
  color: red !important;
}
.card-follows{
  display: flex;
  border: solid 1px;
  border-radius: 5px;
  height: 30px;
  
}
.p{
 display: inline-block;
  font-size: x-small;
}

 
</style>