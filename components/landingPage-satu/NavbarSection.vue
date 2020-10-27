<template>
  <div class="container-header">
    <nav class="navbar navbar-expand-lg navbar-light ">
      <div class="container">
        <a class="navbar-brand" href="#">MY WEBSITE</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav ml-auto">
            <a class="nav-link" href="#">HOME<span class="sr-only">(current)</span></a>
            <a class="nav-link" href="/about">ABOUT US</a>
            <a class="nav-link" href="#">WORK</a>
            <a class="nav-link" href="#" >INFO</a>
            <a class="nav-link btn text-light" href="#" >GET STARTED</a>
          </div>
        </div>
      </div>
    </nav>

  </div>
</template>

<script>
export default {

}
</script>

<style>
 .btn {
   border-radius: 20px;
   background-color: #4FA5BD;
 }


 @media (min-width: 1200px) {
   .nav-link {
     margin-right: 10px;
     font-size: 15px;
   }
  }
</style>