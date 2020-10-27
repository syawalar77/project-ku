<template>
  <div class="container">
    <div class="row">
      <div class="col-md-5 title mr-auto">
        <h1>GLOBAL WARMING</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores explicabo molestiae, sequi quisquam natus corporis voluptates ipsa cupiditate similique commodi facere repudiandae doloribus maxime culpa.</p>
        <Button
          title="klik here" 
        /> 
      </div>
      <img class="img card-columns col-md-5" src="~/assets/image/jumbotronImage.svg" alt="">
    </div>
  </div>
</template>

<script>
import Button from '~/components/atom/Button.vue'
export default {
  components: {
    Button: Button,
  }

}
</script>

<style>
 

  .title {
    margin-top: 300px;
    
  }

  .btn-more {
  margin: 20px auto;
  display: block;
}
/*
 * Card Columns Masonry - Bootstrap 4
 * https://codepen.io/JacobLett/pen/oZmWdd
 */
/* Medium devices (tablets, 768px and up) The navbar toggle appears at this breakpoint */
@media (min-width: 768px) {  
  .card-columns {column-count: 3;}
}
/* Large devices (desktops, 992px and up) */
@media (min-width: 992px) { 
 .card-columns {column-count: 3;}
}
 
/* Extra large devices (large desktops, 1200px and up) */
@media (min-width: 1200px) {  
   .card-columns {column-count: 3;} 
}
@media (max-width: 768px) {  
  .card {
    width: 100%;
  }
}

</style>