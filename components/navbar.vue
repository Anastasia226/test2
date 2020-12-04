<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Nuxt SSR</a>

  <div class="collapse navbar-collapse" >
    <ul class="navbar-nav mr-auto">
      <li class="nav-item ">
          <nuxt-link exact no-prefetch active-class="active" class="nav-link" to="/">
             Home
          </nuxt-link>
        
      </li>
      <li class="nav-item">
         <nuxt-link active-class="active" class="nav-link" to="/about">
             About
          </nuxt-link>
      </li>
       <li class="nav-item">
         <nuxt-link active-class="active" class="nav-link" to="/users">
             Users
          </nuxt-link>
      </li>
       <li class="nav-item">
         <nuxt-link active-class="active" class="nav-link" to="/login">
             Login
          </nuxt-link>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
</nav>
</template>