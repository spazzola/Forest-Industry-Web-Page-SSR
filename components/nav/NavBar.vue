<template>

<!-- <nav class="navbar navbar-expand-xl navbar-light ml-auto">
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse ml-auto" id="navbarTogglerDemo01">
    <ul class="navbar-nav mx-auto text-md-center text-left">
      <li class="nav-item">
        <nuxt-link class="nav-link" active-class="active" to="/aboutcompany">O FIRMIE</nuxt-link>
      </li>
      <li class="nav-item dropdown">
        <router-link class="nav-link dropdown-toggle" active-class="router-link-active" to="" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          OFERTA
        </router-link>
        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
          <nuxt-link class="dropdown-item" active-class="active" to="../../pages/offer/WoodTrading.vue">Handel drewnem</nuxt-link>
          <nuxt-link class="dropdown-item" active-class="active" to="../../pages/offer/LogHomes.vue">Domy z bali</nuxt-link>
          <nuxt-link class="dropdown-item" active-class="active" to="../../pages/offer/TheHunting.vue">Polowania w Rosji</nuxt-link>
          <nuxt-link class="dropdown-item" active-class="active" to="../../pages/offer/TheProgramming.vue">Strony internetowe / aplikacje</nuxt-link>
        </div>
      </li>
      <li class="nav-item">
        <nuxt-link class="nav-link" active-class="active" to="/thegallery">GALERIA</nuxt-link>
      </li>
      <li class="nav-item">
        <nuxt-link class="nav-link" active-class="active" to="/thecontact">KONTAKT</nuxt-link>
      </li>
    </ul>
  </div>
</nav> -->
<div>
  <b-navbar toggleable="lg">
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item>
          <NuxtLink to="/aboutcompany" active-class="active">O FIRMIE</NuxtLink>
        </b-nav-item>

        <b-nav-item-dropdown text="OFERTA" active-class="active">
          <b-dropdown-item href="../../offer/woodtrading">Handel drewnem</b-dropdown-item>
          <b-dropdown-item href="../../offer/loghomes">Domy z bali</b-dropdown-item>
          <b-dropdown-item href="../../offer/thehunting">Polowania w Rosji</b-dropdown-item>
          <b-dropdown-item href="../../offer/theprogramming">Strony iternetowe / aplikacje</b-dropdown-item>
        </b-nav-item-dropdown>

        <b-nav-item>
          <NuxtLink to="/thegallery" active-class="active">GALERIA</NuxtLink>
        </b-nav-item>
        <b-nav-item>
          <NuxtLink to="/thecontact" active-class="active">KONTAKT</NuxtLink>
        </b-nav-item>
      </b-navbar-nav>

    </b-collapse>
  </b-navbar>
</div>
</template>

<script>
export default {};
</script>

<style>

nav {
    max-width: 100%;
    margin-left: 10%;
}


.dropdown-menu {
  background-color: rgb(219, 233, 183);
}

.navbar {
  padding: 0;
  
}

.nav-link {
    color: rgb(136, 158, 129);
    font-weight: bold;
    font-family: 'Libre Baskerville', sans-serif;
}

a, span {
  font-size: 1.4rem;
  color: rgba(0, 0, 0, 0.5);
}

a:hover {
  color: rgb(136, 158, 129) !important;
  text-decoration: none;
}

.active {
  color: black;
}
.navbar-link {
  color: red;
}


 nav .router-link-active,
 nav .router-link-exact-active {
  color: brown;
}

@media only screen and (min-width: 1467px) and (max-width: 1665px) {
  a, span {
    font-size: 1.2rem !important;
  }
}

@media only screen and (min-width: 1285px) and (max-width: 1466px) {
  a, span {
    font-size: 1rem !important;
  }
}

@media only screen and (min-width: 1029px) and (max-width: 1284px) {
  a, span {
    font-size: 0.9rem !important;
  }
}

@media only screen and (max-width: 1028px) {
  a, span {
    margin: 1rem 0 1rem 0 !important;
  }
}

</style>