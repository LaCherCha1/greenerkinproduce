<template>
  <nav class="navbar navbar-expand-xl navbar-dark bg-transparent">
    <h1><a class="navbar-brand" href="#">GreenerKinProduce</a></h1>
    <button
      class="navbar-toggler ml-auto"
      type="button"
      data-toggle="collapse"
      data-target="#mainMenu"
      aria-controls="mainMenu"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="mainMenu">
      <ul class="menu navbar-nav ml-auto">
        <li class="nav-item active">
          <a class="nav-link" href="index.html">
            Home
            <span class="sr-only">(current)</span>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">About Us</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Fruts</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Tropical Oil</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Sustainability</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">News</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Galerry</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact Us</a>
        </li>
        <!-- <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Dropdown
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="#">Something else here</a>
        </div>
        </li>-->
      </ul>
    </div>
  </nav>
 
</template>

<script>
export default {
  name: "MainMenu",
};
</script>

<style scoped>
nav{
	position: absolute;
    width: 100%;
    padding: 1em 2em;
	box-shadow: 0 0 4px #969595;
}
li{
	font-family: 'Mada', sans-serif;
}
h1{
	font-family: 'Poiret One', cursive
}
.navbar-brand{
    font-weight: 700;
    font-size: 35px;
}
@media (max-width: 1199px) { 
  .collapse{
    background-color: rgba(255, 255, 255, .95);
    z-index: 9999;
  }
  .collapse ul{
    text-align: center;
    float: inherit;
  }
  .collapse a {
    color:black !important;
    font-size: 1rem;
    
  }
 }

</style>