<template>
  <div>
    <nav-menu></nav-menu>
    <div>
      <h1>O firmie</h1>
      <div class="content">
        Tworząc naszą historię silny nacisk stawiamy na budowaniu grupy
        zaufanych klientów. Dobra renoma oraz zadowolenie klientów, są dla nas
        podstawą własciwie funkcjonującego przedsiębiorstwa.
        <br />
        <br />
        Zajmujemy się wszelkimi pracami związanymi z gospodarką leśną, handlem
        drewna oraz budową domów z bali. Dodatkowo oferujemy sprzedaż węgla typu ekogroszek.
        Nasze składnice
        znajdują się na terenie Europy oraz Azji.
        <br />
        Dążymy do ciągłego rozwoju. Nie boimy się nowych wyzwań, ani
        innowacyjnych technologii. Dlatego w naszej ofercie znajdą Państwo
        strony www, dedykowane aplikacje internetowe, mobilne i desktopowe,
        które sprostają najwyższym standardom. <br />
        <br />
      </div>
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
      title: "Forest Industry S.A.",
    };
  },
  components: {
    NavMenu,
    TheFooter
  },
};
</script>

<style scoped>
h1 {
  margin-top: 3rem;
  text-align: center;
  font-family: "Merriweather", serif;
}

.content {
  text-align: center;
  max-width: 50%;
  margin: auto;
  margin-top: 2rem;
  line-height: 1.5;
  margin-bottom: 5rem;
  font-size: 1.15rem;
}

@media (max-width: 1028px) {
  .content {
    max-width: 90%;
  }
}
</style>