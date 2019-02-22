<template>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">PIZZA PALACE</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
    <i class="fas fa-hamsa"></i>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavDropdown">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link" href="#">Menu<span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Order</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Location</a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Contact us
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
          <a class="dropdown-item" href="#"><i class="fas fa-phone-square"></i> Call</a>
          <a class="dropdown-item" href="#"><i class="fas fa-comment-alt"></i> Text</a>
          <a class="dropdown-item" href="#"><i class="fas fa-envelope"></i> E-mail</a>
        </div>
      </li>
    </ul>
  </div>
</nav>
</template>

<script>
export default {
  name: 'NavBar',
}
</script>

<style scoped>
  .navbar, .dropdown-menu, .navbar-toggler{
    background-color: var(--elite-bgColor) !important;
    color: var(--main-text) !important;
  }

  .navbar-light .navbar-nav .nav-link{
  background-color: var(--elite-bgColor);
  color: var(--main-text);
  }

  .navbar a{
  background-color: var(--elite-bgColor);
  color: var(--main-text);
  }

  a.navbar-brand:hover, .fa-hamsa:hover, .nav-link:hover, .dropdown-item:hover{
    color: #09f !important;
  }

  .navbar-brand{
    text-shadow: 2px 2px #d6943e;
  }
</style>