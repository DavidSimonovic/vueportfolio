<template>
<div  id="home">
  <div class="container" id='entry-header'>
    
  <h1> Hello my name is </h1>
 
  <h1>David Simonovic </h1>
 
  <h1> I'm a Full stack developer</h1>
    

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
      height: 100vh;
      
  }


#entry-header {

  padding-top: 10%;
  text-align: center;
  font-family: 'Monoton', cursive;
  
  color: white;
  text-shadow: 0px 0px 10px yellow;
} 
img {
  max-height: 20vh;
  max-width: 30vh;
  float: center;
}
#entry-header h1{
  font-size: 3.5rem;
}

</style>
