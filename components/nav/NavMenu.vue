<template>
  <div class="row shadow">
    <div class="col-lg-2 col-md-6">
      <img src="../../static/logo.png" class="logo" alt="logo" />
    </div>

    <div class="col-lg-4 col-md-6 center">
      <img src="../../static/header.png" class="header" alt="header" />
    </div>

    <div class="col-6 nav-menu center pnav">
      <nav-bar></nav-bar>
    </div>
  </div>
</template>

<script>
import NavBar from "./NavBar.vue";

export default {
  components: {
    NavBar,
  },
};
</script>

<style scoped>
.header {
  max-width: 100%;
  max-height: 100%;
  position: relative;
  left: 4%;
  z-index: 1;
}

.logo {
  width: 90%;
  height: 85%;
  margin-top: 3%;
}

.row {
  background-color: rgb(219, 233, 183);
  text-align: center;
}

.center {
  margin: auto;
  text-align: center;
}

.shadow {
  box-shadow: 10px 10px 5px grey;
}

@media (max-width: 1028px) {
  .header {
    margin-top: 5%;
    left: 0%;
    padding-left: 15px;
    padding-right: 15px;
  }
}

@media (max-width: 991px) {
  .pnav {
    display: flex;
    justify-content: center;
  }
}
</style>
