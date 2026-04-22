<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      
      <!-- BRAND -->
      <router-link class="navbar-brand" to="/">Company NR</router-link>

      <!-- TOGGLER -->
      <button 
        class="navbar-toggler" 
        type="button" 
        data-bs-toggle="collapse" 
        data-bs-target="#navbarSupportedContent">
        <span class="navbar-toggler-icon"></span>
      </button>

      <!-- MENU -->
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">

          <li class="nav-item">
            <router-link class="nav-link" to="/">Home</router-link>
          </li>

          <li class="nav-item">
            <router-link class="nav-link" to="/portofolio">Portofolio</router-link>
          </li>

          <li class="nav-item">
            <router-link class="nav-link" to="/about">About</router-link>
          </li>

          <li class="nav-item">
            <router-link class="nav-link" to="/contact">Contact</router-link>
          </li>

        </ul>

        <!-- SEARCH -->
        <form class="d-flex">
          <input 
            class="form-control me-2" 
            type="search" 
            placeholder="Search"
          />
          <button class="btn btn-outline-light" type="submit">
            Search
          </button>
        </form>
      </div>
    </div>
  </nav>
</template>

<style>

.navbar.bg-body-tertiary {
  background-color: #213547 !important;
}


.navbar.bg-body-tertiary .navbar-brand,
.navbar.bg-body-tertiary .nav-link {
  color: #ffffff !important;
}


.navbar.bg-body-tertiary .nav-link:hover {
  color: #9fd3ff !important;
}


.navbar.bg-body-tertiary .navbar-toggler {
  border-color: rgba(255,255,255,0.5);
}

.navbar.bg-body-tertiary .navbar-toggler-icon {
  filter: invert(1);
}
 
</style>
