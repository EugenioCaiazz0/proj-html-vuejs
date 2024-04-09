<script>
/*import  from 
export default {
  components: {
  },
  mounted() {},
};*/
</script>

<template>

<!--1 Jumbotron-->
<div class="container d-flex" id="1Jumbotron">
    <div style="padding-left: 15%; width: 50%;" class="align-content-center"> 
        <h1> Udemy Affiliate Sales</h1>
        <h5> Monetize your audience and attract new customers with Udemy!</h5>
    </div>
    <div style="width: 50%;">
        <img class="float-end" src="./images/naassom-azevedo-Q_Sei-TqSlc-unsplash.jpg" alt="Foto di Naassom Azevedo su Unsplash" style="width: 100%; height: 400px; object-fit: cover;">
    </div>
</div>

 <!--popular dev courses-->
 <div class="container" style="height: 600px;"> <!--semplificare la struttura?-->
    <h3 style="font-weight: bold;"> Popular development courses</h3>
    <!--card da replicare 270x170x360, fare il componente???-->
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
            <p class="oldPrice">199.99$</p> <!--aggiungere classe oldprice-->
            <p>$100</p>
          </div>
        </div>
      </div>
    </div>
  </div>

<!--2 Jumbotron-->
<div class="container-fluid d-flex" id="2Jumbotron">
  <div class="d-flex flex-column" style="padding-left:15%; padding-top: 140px;">
    <h1> Limitless learning, <br> more possibilities</h1>
    <p> Online courses open the opportunity for learning to almost anyone, <br>
        regardless of their scheduling committments. </p>
    <button type="button" class="btn" id="readMoreBtn"> READ MORE </button>    
    </div>
  </div>

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

#readMoreBtn{
  background-color: #ff4550; 
  width: fit-content; 
  color: white; 
  padding: 15px; 
  padding-top: 15px; 
  font-size: large;
}

.card{
  height: 360px; 
  width: 270px;
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
</style>