<script>
    export default {
        props: {
            cardName: String,
            cardImage: String,
            cardNewPrice: String,
            cardOldPrice: String,
            cardText: String
        }
    }
</script>

<template>

<div class="card">
    <img :src="cardImage" :alt="cardName" class="card-img-top">
    <div class="card-body">
      <p class="card-title"> {{ cardName }} ></p>
      <p class="card-text"> {{ cardText }} </p> 
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
          <p class="oldPrice">{{cardOldPrice}}</p> 
          <p>{{ cardNewPrice }}</p>
        </div>
      </div>
    </div>
  </div>

</template>


<style>

    .card{
        height: 360px; 
        width: 270px;
        margin-right: 20px; }

</style>
