<template>
  <div id="projects">
      <div class="container">
          <div class="row">
              <div class="col-md-6 col-12">

       <a href="https://github.com/DavidSimonovic/uora">  <div class="card">
            <div class="card-body">
         <img class="card-img-top" src="../img/uors.png" alt="">
          
           
        </div>
        <div class="card-footer text-center">
            <h1>Laravel</h1>
        </div>
        </div>
</a>
              </div>   

              <div class="col-md-6 col-12">

        <a href="https://github.com/DavidSimonovic/cmspdo"><div class="card">
            <div class="card-body">
          <img class="card-img-top" src="../img/main.png" alt="">
          
           
        </div>
        <div class="card-footer text-center">
            <h1>PHP</h1>
        </div>
        </div>
        </a>

              </div>   

          </div>

             <div class="row">
              <div class="col-md-6 col-12">

        <a href="https://github.com/DavidSimonovic/reactportfolio"> <div class="card">
            <div class="card-body">
         <img class="card-img-top" src="../img/oldport.png" alt="">
          
           
        </div>
        <div class="card-footer text-center">
            <h1>React.js</h1>
        </div>
        </div>
</a>
              </div>   

              <div class="col-md-6 col-12">

        <a href="https://github.com/DavidSimonovic/vueportfolio"><div class="card">
            <div class="card-body">
          <img class="card-img-top" src="../img/newport.png" alt="">
          
           
        </div>
        <div class="card-footer text-center">
            <h1>Vue.js</h1>
        </div>
        </div>
        </a>

              </div>   

          </div>




      </div>
  </div>
</template>

<script>
export default {
    name: 'Projects'
}
</script>

<style>
#projects{
    background-color: #1EA896;
    padding-top: 15vh;
    padding-bottom: 15vh;
}
#projects .card{
   
    margin-top: 5vh;
    background-color: lightgrey !important;
}
#projects h1{
     font-size: 1.4rem;
     font-family: 'Montserrat Alternates', sans-serif;
}
#projects a:hover{
   box-shadow: 0px 0px 15px yellow;
   text-decoration: none !important;
 }
</style>