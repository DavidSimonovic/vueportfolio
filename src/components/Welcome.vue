<template>
<div  id="home">
  <div class="container" id='entry-header'>
  <h1>David Simonovic</h1>
  <h1>Full stack developer</h1>
  
   <img class="card-img-top" src="../img/welcome.png" alt="">

  </div>
</div>
</template>

<script>


export default {
  name: 'Welcome',
  
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #home
  {
      font-family: 'Montserrat Alternates', sans-serif;
      background-color: #1EA896;
      padding-top:10vh;
      
  }
#entry-header {
  height: 100vh;
  
  text-align: center;
  font-family: 'Montserrat Alternates', sans-serif;
  
  
  color: white;
  text-shadow: 0px 0px 2px yellow;
} 
#entry-header h1{
  font-size: 3rem;
  padding-top: 20px;
  
  
}

</style>
