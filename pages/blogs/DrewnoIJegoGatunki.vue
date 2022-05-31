<template>
  <div>
    <nav-menu></nav-menu>
    <div class="content">

  <h1>Drewno i jego gatunki — co można z niego wykonać?</h1>
<img class="post_image" src="../../static/drewnogatunki.jpg" alt="kłody drewna sosnowego">
  <p style="text-align: justify">Drewno towarzyszy człowiekowi od niepamiętnych czasów. Pochodzenie, sposób pozyskania i właściwości fizyczne drewna sprawiają, że jest ono najbardziej naturalnym, a także przyjaznym materiałem, który wykorzystuje się na skalę globalną. Znajduje zastosowanie w wyposażaniu wnętrz, konstrukcji domów, a także wykorzystywane jest w celach grzewczych.</p>
  <p style="text-algin: justify;">Do najpopularniejszych gatunków drewna należą:</p>
  <ul style="text-align: justify;">
  <li><strong>drewno świerkowe</strong> — jest surowcem miękkim i lekkim, łatwo poddającym się obróbce. Jego atutem jest trwałość oraz wytrzymałość – bowiem materiał ten można malować, a także lakierować. Świerk syberyjski porasta tereny od północnej części Półwyspu Skandynawskiego, przez całą Syberię, aż po wybrzeża Morza Ochockiego — stamtąd jest często transportowany do innych zakątków świata, w tym również do Polski.</li>
  <li><strong>modrzew syberyjski</strong> — oprócz wysokiej wytrzymałości, posiada naturalną odporność na grzyby, dzięki temu można stosować go na zewnątrz budynków, gdyż wykazuje się dużą odpornością na działanie niekorzystnych warunków atmosferycznych. Nie ulega zniszczeniu nawet pod wpływem wilgoci i wody, więc całkowicie można zrezygnować z jego konserwacji środkami chemicznymi.</li>
  <li><strong>cedr syberyjski</strong> — to jedno z najpiękniejszych i największych drzew Syberii. Jest bezproblemowe w obróbce, doskonale przewodzi ciepło oraz cechuje się wysoką wodoodpornością — to ekologiczny materiał, który nie gnije. Drewno cedrowe po wysuszeniu i zagruntowaniu dobrze przyjmuje powłoki lakiernicze, farby, impregnaty i bejce.</li>
  <li><strong>sosna</strong> — jest najliczniejszym gatunkiem drzew w Polsce, rośnie szybko i jest łatwa w obróbce. Drewno sosnowe można strugać, szlifować, a także bez żadnego problemu frezować — przybiera wtedy nawet najbardziej nietypowe, fantazyjne kształty. Zapewnia dobrą izolację termiczną i akustyczną oraz szybko schnie – dlatego łatwo pokryć je farbą. W aspekcie konstrukcyjnym sosna jest podobna do cedru syberyjskiego. Drewno sosnowe wykazuje właściwości elektrostatyczne — nie przyciąga kurzu, a również zapobiega jego kłębieniu się w powietrzu, jest szczególnie polecane osobom ze skłonnością do alergii.</li>
  </ul>


  <h2>Co można wykonać z tych gatunków drewna?</h2>
  <p style="text-align: justify;">Drewno świerków syberyjskich jest jednym z bardziej znanych, które dostępne są na rynku stolarskim. Warto wiedzieć, że właśnie ten rodzaj przeznacza się na drewno okleinowe jako deski okładzinowe, a także deski konstrukcyjne w celach budowlanych. Natomiast drewno z modrzewia syberyjskiego używane jest do elewacji, produkcji tarasów i mebli ogrodowych. To też świetny materiał do budowy sauny. Z kolei domy zbudowane z cedru mogą przetrwać setki lat i mają korzystny wpływ na zdrowie ich właścicieli. Do wyrobu drewna stosuje się nowoczesne linie produkcyjne, pozwalające na to, aby belka miała idealną powierzchnię. Materiał, jakim jest drewno pozyskiwane z drzewa sosnowego jest tanie i ekologiczne, dlatego cieszy się bardzo dużą popularnością. Wykorzystuje się je do tworzenia drzwi, mebli, a także podłogi.</p>
  <p style="text-align: justify">Jak widać, drewno to bardzo popularny surowiec stosowany do produkcji wielu przedmiotów codziennego użytku. Wykonuje się z niego zarówno duże konstrukcje, jak i drobne przedmioty. Jest eleganckim, trwałym, naturalnym oraz łatwo dostępnym materiałem o licznych zastosowaniach. Przed zakupem odpowiedniego gatunku warto poznać jego właściwości.</p>



</div>
    <the-footer></the-footer>
  </div>
</template>

<script>
import NavMenu from "../../components/nav/NavMenu.vue";
import TheFooter from "../../components/TheFooter.vue";

export default {head() {
    return {
      title: "Drewno i jego gatunki — co można z niego wykonać? | Forest Industry S.A.",
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
  width: 400px;
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
