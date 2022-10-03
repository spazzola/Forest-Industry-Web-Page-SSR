<template>
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
          <b-dropdown-item href="../../offer/coaltrading">Handel węglem</b-dropdown-item>
          <b-dropdown-item href="../../offer/loghomes">Domy z bali</b-dropdown-item>
          <!-- <b-dropdown-item href="../../offer/thehunting">Polowania w Rosji</b-dropdown-item> -->
          <b-dropdown-item href="../../offer/theprogramming">Strony internetowe / aplikacje</b-dropdown-item>
        </b-nav-item-dropdown>

        <b-nav-item>
          <NuxtLink to="/thegallery" active-class="active">GALERIA</NuxtLink>
        </b-nav-item>
        <b-nav-item>
          <NuxtLink to="/thecontact" active-class="active">KONTAKT</NuxtLink>
        </b-nav-item>
        <b-nav-item>
          <NuxtLink to="/blog" active-class="active">BLOG</NuxtLink>
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

button {
  border: 2px solid rgb(90, 98, 73) !important;
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