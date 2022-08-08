<template>
  <div>
    <nav-menu></nav-menu>
    <div class="content">
    <h1>Nauka nie pójdzie w las — charakterystyka świerka syberyjskiego</h1>
    <img class="post_image modrzew" src="../../static/swierksyb.jpg" alt="Świerk syberyjski">
    <p style="text-align: justify;">Im dalej w las, tym więcej drzew — a dzisiaj na tapecie znalazł się miłośnik zimnego i umiarkowanego klimatu. Świerk syberyjski, bo o nim tu mowa, jest rośliną pospolitą mającą nawet kilkaset gatunków oraz kilkanaście rodzajów. W swojej prostocie skrywa piękno, które najbardziej uwydatnia się w domach z drewna. O pochodzeniu, wyglądzie oraz zastosowaniu Picea obovata (świerku syberyjskiego) opowiemy już teraz.</p>
    <h2>Świerk syberyjski: pochodzenie</h2>
    <p style="text-align: justify;">Świerk syberyjski uwielbia lekki chłodek, toteż jego naturalnym miejscem występowania jest Azja, a konkretniej Syberia, Kazachstan, Mongolia oraz północna część Chin. Niemniej jednak Picea obovata spotykany jest także w Polsce i wielu innych krajach. To głównie dlatego, że jest to roślina uprawiana w celach dekoracyjnych, głównie do zdobienia parków i ogrodów. Świerk syberyjski nie jest rośliną wymagającą, ale z pewnością bardzo efektowną. Można go łatwo pomylić ze świerkiem pospolitym, który w Polsce jest jednym z najczęściej występujących gatunków.
</p>

        <h2>Świerk syberyjski: wygląd</h2>
    <p style="text-align: justify;">Picea obovata należy do drzew dużych, a to dlatego, że jego wysokość sięga nawet 60 metrów! Pozyskiwane ze świerku syberyjskiego drewno jest jasne oraz elastyczne. Charakteryzuje się dość dużym połyskiem ze względu na posiadane wyraźnie widoczne przewody żywiczne — można je zaobserwować jako cienkie kreski w przekroju podłużnym i błyszczące punkty w przekroju poprzecznym. Kolor deski może się zmienić pod wpływem czynników atmosferycznych, najczęściej pogłębia się lub nabiera więcej odcieni szarości. Każde drewno pozyskane z Picea obovata ma nieco inną barwę — jaśniejszą bądź ciemniejszą — a dodatkowo może posiadać ciemne plamy, które naturalnie pojawiają się ze względu na uprawę w klimacie środkowo-europejskim. Nie bez powodu wiele osób, chcących wykonać posadzkę w eleganckim stylu, wybiera właśnie świerk syberyjski. Drewno to nadaje bowiem harmonijny charakter i wprowadza sielankowy klimat.</p>

        <h2>Świerk syberyjski: zastosowanie</h2>
    <p style="text-align: justify;">Skoro przy aranżacji jesteśmy — gdzie tak naprawdę można wykorzystać świerk syberyjski? Deska pozyskana z tego drzewa doskonale nadaje się jako okładzina elewacyjna. Można wykorzystać również to drewno do innych celów budowlanych: stworzenia eleganckich schodów czy podłóg. Często stosuje się świerk syberyjski na taras — ozdobiony pięknymi kwietnikami i bujanym fotelem oczaruje niejedną osobę. Z mniejszych przedmiotów warto na pewno wspomnieć o instrumentach muzycznych, które to swój piękny wygląd i czyste brzmienie zawdzięczają między innymi tej roślinie. Z kolei jeżeli chodzi o większe konstrukcje, szczerze powiemy, że materiał ten doskonale nadaje się na domy. Świerk syberyjski może być wykorzystany do stworzenia zarówno domków letniskowych, jak i całorocznych. Gwarantujemy przepiękny efekt!</p>
        <p style="text-align: justify;">Tutaj kończy się nasza podróż po lesie świerkowym. Mamy nadzieję, że przekonaliśmy Cię do zainteresowania się tematem drewna z Picea obovata. Jest to z pewnością wybór dla osób, które lubią styl rustykalny bądź chcą urządzić na swoim tarasie oazę spokoju w przyjemnej otoczce. Nic nie stoi na przeszkodzie, aby posunąć się o krok dalej i od podstaw stworzyć niesamowity dom z bali świerku syberyjskiego! Zapraszamy do kolejnych naszych wpisów — może to w nich znajdziesz swojego faworyta?</p>
</div>
    <the-footer></the-footer>
  </div>
</template>

<script>
import NavMenu from "../../components/nav/NavMenu.vue";
import TheFooter from "../../components/TheFooter.vue";

export default {head() {
    return {
      title: "Nauka nie pójdzie w las — charakterystyka świerka syberyjskiego | Forest Industry S.A.",
    };
  },
  components: {
    NavMenu,
    TheFooter,
  },
};
</script>

<style scoped>
.content {
  text-align: center;
  max-width: 50%;
  margin: auto;
  margin-top: 2rem;
  line-height: 1.5;
  margin-bottom: 5rem;
  padding: 0 20px;
  font-size: 1.15rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
} 

.post_image {
  margin: 20px;
}

.post_image.modrzew {
  max-width: 600px;
}

@media(max-width: 600px) {
  .post_image{
    max-width: 300px;
  }

  .content {
    max-width: 90%;
  }
}
</style>
