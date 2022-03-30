<template>
    <div>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">
      <img src="/images/phoenix.png" class="logo-img" alt="">
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <!-- <a class="nav-link active" aria-current="page" href="#">Home</a> -->
          <NuxtLink class="nav-link active" to="/">Home</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink class="nav-link" to="/about">About Us</NuxtLink>

        </li>
        <li class="nav-item">
          <NuxtLink class="nav-link" to="/service">Service</NuxtLink>

        </li>

<li class="nav-item">
          <NuxtLink class="nav-link" to="/contact">Contact Us</NuxtLink>

        </li>

      </ul>
    </div>
  </div>
</nav>

    </div>
</template>

<script>
export default {
name:'AppHeader'
    
}
</script>

<style>
.logo-img{
  width: 170px;
}
</style>