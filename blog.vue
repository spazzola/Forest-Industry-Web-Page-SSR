<template>
  <div>
    <nav-menu></nav-menu>

    <div
      class="content"
      style="display: flex; flex-direction: column; align-items: center"
    >
      <h1>Blog</h1>
      <ul class="post_container">
        <li class="post">
          <div class="post_thumbnail">
            <img src="../static/domzbali.jpg" alt="domy z bali" />
          </div>
          <p class="post_title">
            Dom z bali — dlaczego stał się tak popularny?
          </p>
          <p class="post_excerpt">
            Domy z bali to ciekawa propozycja architektoniczna i choć kojarzy
            się z zabudowaniami na wsiach oraz w rejonach górskich...
          </p>
          <a href="/blogs/domyzbali">Czytaj więcej</a>
        </li>
      </ul>
    </div>
    <the-footer></the-footer>
  </div>
</template>

<script>
import NavMenu from "../components/nav/NavMenu.vue";
import TheFooter from "../components/TheFooter.vue";

export default {
  head() {
    return {
      title: "Blog | Forest Industry S.A.",
    };
  },
  components: {
    NavMenu,
    TheFooter,
  },
};
</script>

<style>
.post_container {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 50%;
  list-style-type: none;
  margin-top: 40px;
  flex-wrap: wrap;
}

.post {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  width: 300px;
  margin: 0 10px 30px;
}

.post_thumbnail {
  width: 300px;
}

.post_thumbnail img {
  width: 100%;
}

.post_title {
  font-weight: bold;
  font-size: 18px;
  margin: 10px 0 5px;
}

.post_excerpt {
  font-size: 16px;
}

.post_title,
.post_excerpt {
  text-align: left;
}

.content {
  text-align: left;
  max-width: 30%;
  margin: auto;
  margin-top: 2rem;
  line-height: 1.5;
  margin-bottom: 5rem;
  font-size: 1.15rem;
}

body {
  overflow-x: hidden;
}
</style>
