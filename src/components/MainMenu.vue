<template>
  <nav class="navbar navbar-expand-xl navbar-dark bg-transparent">
    <h1><a class="navbar-brand" href="#">GreenerKinProduce</a></h1>
    <button
      class="navbar-toggler ml-auto"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="menu navbar-nav ml-auto">
        <li class="nav-item active">
          <a class="nav-link" href="index.html">
            Home
            <span class="sr-only">(current)</span>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About Us</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="fruts.html">Fruts</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="fruts.html">Tropical Oil</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="service.html">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="service.html">Sustainability</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="service.html">News</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="service.html">Galerry</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact Us</a>
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

</style>