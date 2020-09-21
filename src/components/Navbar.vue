<template>
   <nav class="navbar navbar-expand-md navbar-dark">
      <a class="navbar-brand" href="https://github.com/DavidSimonovic">David Simonovic</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarCollapse">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <a class="nav-link" href="#skills">Skills</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#projects">Projects</a>
          </li>
           <li class="nav-item">
            <a class="nav-link" href="#about">About & Contact</a>
          </li>
         
        </ul>
    </div>
    </nav>

</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style>
a{

  font-family: 'Montserrat Alternates', sans-serif;

}
nav a:hover{
    text-shadow: 0px 0px 5px yellow;
}
.navbar {
    background-color: #191516 !important;
    
}

</style>