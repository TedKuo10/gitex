<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Navbar</a>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link to="/admin" class="nav-link">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/admin/products" class="nav-link">Products</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/" class="nav-link">前台</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <div>
    <h1 class="h1">後台</h1>
  </div>
  <router-view></router-view>
</template>
