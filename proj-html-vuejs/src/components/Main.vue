<script>
export default {}
</script>

<template>

<!--1 Jumbotron-->
<div class="container d-flex" id="1Jumbotron">
    <div style="padding-left: 15%; padding-top: 100px; width: 50%;" class="align-content-center"> 
        <h1> Udemy Affiliate Sales</h1>
        <h5> Monetize your audience and attract new customers with Udemy!</h5>
    </div>
    <div style="width: 50%;">
        <img class="float-end jumbo1" src="./images/naassom-azevedo-Q_Sei-TqSlc-unsplash.jpg" alt="Foto di Naassom Azevedo su Unsplash">
    </div>
</div>

 <!--popular dev courses-->
 <div class="container" style="height: 600px;"> <!--semplificare la struttura?-->
    <h3 style="font-weight: bold; padding-top: 90px; padding-bottom: 40px;"> Popular development courses</h3>
    <!--card da replicare 270x170x360, fare il componente???-->
    
    <div class="container d-flex flex-row">
      
      <div class="card">
        <img src="./assets/images/895786_7b4b_2-272x161.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <p class="card-title">Development ></p>
          <p class="card-text">The complete iOS10 & Swift3 Developer Course</p> 
          <br>
          
          <div class="d-flex justify-content-between">
            <p> 
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-regular fa-star-half-stroke"></i>
            </p>
            <div>
              <p class="oldPrice">199.99$</p> <!--aggiungere classe oldprice-->
              <p>$100</p>
            </div>
          </div>
        </div>
      </div>

      <div class="card">
        <img src="./assets/images/246154_d8b0_3-272x161.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <p class="card-title">Lorem ></p>
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic, consequuntur?</p> 
          <br>
          
          <div class="d-flex justify-content-between">
            <p> 
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-regular fa-star-half-stroke"></i>
            </p>
            <div>
              <p class="oldPrice">199.99$</p> 
              <p>$100</p>
            </div>
          </div>
        </div>
      </div>

      <div class="card">
        <img src="./assets/images/752950_b773-272x161.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <p class="card-title">Lorem ></p>
          <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi, reiciendis.</p> 
          <br>
          
          <div class="d-flex justify-content-between">
            <p> 
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-regular fa-star-half-stroke"></i>
            </p>
            <div>
              <p class="oldPrice">199.99$</p> 
              <p>$100</p>
            </div>
          </div>
        </div>
      </div>

      <div class="card">
        <img src="./assets/images/1253188_58f7_2-272x161.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <p class="card-title">Lorem ></p>
          <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto, iste!</p> 
          <br>
          
          <div class="d-flex justify-content-between">
            <p> 
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-regular fa-star-half-stroke"></i>
            </p>
            <div>
              <p class="oldPrice">199.99$</p> 
              <p>$100</p>
            </div>
          </div>
        </div>
      </div>

      <div class="card">
        <img src="./assets/images/placeholder.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <p class="card-title">Lorem ></p>
          <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto, iste!</p> 
          <br>
          
          <div class="d-flex justify-content-between">
            <p> 
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-regular fa-star-half-stroke"></i>
            </p>
            <div>
              <p class="oldPrice">199.99$</p> 
              <p>$100</p>
            </div>
          </div>
        </div>
      </div>

      <div class="card">
        <img src="./assets/images/placeholder.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <p class="card-title">Lorem ></p>
          <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto, iste!</p> 
          <br>
          
          <div class="d-flex justify-content-between">
            <p> 
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-regular fa-star-half-stroke"></i>
            </p>
            <div>
              <p class="oldPrice">199.99$</p> 
              <p>$100</p>
            </div>
          </div>
        </div>
      </div>

    </div>  

  </div>
<!-- popular dev courses -->

<!--2 Jumbotron-->
  <div class="container-fluid d-flex" id="2Jumbotron">
    <div class="d-flex flex-column" style="padding-left:15%; padding-top: 140px;">
      <h1> Limitless learning, <br> more possibilities</h1>
      <p> Online courses open the opportunity for learning to almost anyone, <br>
          regardless of their scheduling committments. </p>
      <button type="button" class="btn" id="redBtn"> READ MORE </button>    
    </div>
  </div>

  <!--recent courses-->
  <div class="container-fluid d-flex flex-column justify-content-center" style="width: 55%">
   
    <ul class="d-flex flex-row">
      <li>All Categories</li> <!--font-size dinamica???-->
      <li>Business</li>
      <li>Design</li>
      <li>Development</li>
      <li>IT & Software</li>
      <li>Lifestyle</li>
      <li>Marketing</li>
      <li>Office Productivity</li>
    </ul>
   
    <div class="container-fluid">
      
      <div class="card">
        <img src="..." class="card-img-top" alt="...">
        <div class="card-body">
          <p class="card-title">Development ></p>
          <p class="card-text">The complete iOS10 & Swift3 Developer Course</p>
          <br>
          <div class="d-flex justify-content-between">
            <p> 
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-regular fa-star-half-stroke"></i>
            </p>
          <div>
            <p class="oldPrice">199.99$</p> 
            <p>$100</p>
          </div>
        </div>
      </div>
    </div>
  </div> 
    <button type="button" class="btn redBtn"> SHOW ALL</button>
  </div>
<!--recent courses-->

<!--newsletter-->
  <div class="container-fluid d-flex" id="newsletter"> 
  <div class="d-flex" style=" width: 60%; ">

    <div style="width: 50%;">
      <h4> Subscribe to our newsletter</h4>
      <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. 
          Aliquam odio eius, dolor sit quidem asperiores quia itaque incidunt vel accusantium, facilis odit quo quae.</p>
    </div>        
            
    <div class="d-flex flex-column" style="width:50%">
      <h5>YOUR E-MAIL ADDRESS</h5>
      <div class="input-group ">
        <input type="text" class="form-control" placeholder="Enter your E-mail" aria-label="" aria-describedby="">
        <button class="btn" type="button" id="" style="padding: 10px; background-color: #334453; color: white;"> Subscribe </button>
      </div>
    </div>

  </div>
  </div>
<!--newsletter-->

<!--popular courses-->
<div class="container-fluid d-flex flex-column justify-content-center" id="popularCourses">
  <h1 style="padding-top: 110px;">Popular Courses</h1>
  <p> Discover our most popular courses for self learning</p>
  
  <div class="container d-flex flex-row flex-wrap">
    
    <div class="card">
      <img src="..." class="card-img-top" alt="...">
      <div class="card-body">
        <p class="card-title">Development ></p>
        <p class="card-text">The complete iOS10 & Swift3 Developer Course</p>
        <br>
        <div class="d-flex justify-content-between">
          <p> 
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-regular fa-star-half-stroke"></i>
          </p>
        
          <div>
            <p class="oldPrice">199.99$</p>
            <p>$100</p>
          </div>
        </div>
      </div>
    </div>

  </div>

</div>
<!--popular courses-->

<!--call to action-->
<div class="container-fluid d-flex flex-row align-items-center " style="height: 525px;">
        
  <div class="d-flex advertisementCard" style="margin-left: 90px; margin-right: 15px;">
    <img src="images/image_box_1-221x231.png" alt="">
    <div class="d-flex flex-column" style="width: 550px;">
      <h4> Become an Instructor </h4>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Est quo commodi totam? Iure, atque ut.</p>
      <button type="button" class="btn redBtn"> START TEACHING </button>   
    </div> 
  </div>

  <div class="d-flex advertisementCard" style="margin-left: 15px; margin-right: 90px;">
    <img src="images/image_box_2-234x231.png" alt="">
    <div class="d-flex flex-column" style="width: 550px;">
      <h4> Access for business </h4>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Est quo commodi totam? Iure, atque ut.</p>
      <button type="button" class="btn redBtn"> DOING BUSINESS </button>    
    </div>
  </div>

</div>
<!--call to action-->

<!--advertisement-->
<div id="advertisementBottom" class="container-fluid">
  <div class="d-flex flex-column align-items-center advertisementTextbox">
    <h4 style="padding-top: 100px;"> Investing For Your Future</h4>
    <p style="color: gray; padding: 30px 100px;"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae praesentium autem nulla natus numquam sunt similique error sed suscipit alias neque consectetur voluptas omnis deserunt dolorem excepturi debitis, fugit itaque dolores quam consequatur veritatis accusamus?</p>
    <div style="align-self: flex-start; padding-left: 100px;">
      <h5> Linda Green </h5>
      <p> Product Manager, Apple Inc</p>
    </div>
  </div>
</div>
<!--advertisement-->


</template>

<style lang="scss" scoped>

#1Jumbotron{
  background-color: #ff4550; 
  color: white; 
  height: 400px;
  text-align: center;
  line-height: 100%;
}

#2Jumbotron{
  height: 530px; 
  background-image: url(./assets/images/bg.png); 
  background-position: 75% 75%;
}

#newsletter{
  height: 170px; 
  background-color: #ff4550; 
  color: white; 
  padding-top: 35px; 
  margin-top: 110px;
}

#popularCourses{
  height: 740px;
}

#advertisementBottom{
  background-image: url(images/testimonial-1-1917x640-1-1914x639.jpg); 
  background-size: cover; 
  height: 670px; 
  position: relative;
}

.redBtn{
  background-color: #ff4550; 
  width: fit-content; 
  color: white; 
  padding: 15px; 
  padding-top: 15px; 
  font-size: large;
}

ul li{
  list-style: none;
  margin-right: 10px;
  margin-left: 10px;
}

.card{
  height: 360px; 
  width: 270px;
  margin-right: 20px;
}

.advertisementCard{
  height: 375px; 
  width: 850px; 
  border: 1px solid gray;
}

.advertisementTextbox{
  width: 730px; 
  height: 530px;
  position: absolute; 
  left: 20%; 
  top:10%; 
  background-color: white;
}

.card-img-top{
  height: 170px; 
  width: 270px;
}

.oldPrice{
  font-size: small;
  text-decoration: line-through;
  color: gray;
}

.fa-star{
  color: yellow;
}

.jumbo1{
  width: 100%;
  height: 400px; 
  object-fit: cover;
}


</style>