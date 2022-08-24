<template>
  <div>
    <nav-menu></nav-menu>
    <div class="content">
  
  <h1>Nauka nie pójdzie w las — charakterystyka cedru syberyjskiego</h1>
<img class="post_image modrzew" src="../../static/cedrsyb1.jpg" alt="cedr syberyjski">
  <p style="text-align: justify">Monumentalne drzewo zwane uzdrowicielem i żywicielem. Przed laty mówiono o nim jako o królu tajgi, który w cieniu swych bujnych gałęzi skrywał wiele młodych roślin, a także dawał schronienie zwierzynie. Cedr syberyjski, zwany także sosną syberyjską lub limbą syberyjską, to pełne mroku i tajemniczości drzewo o dużych walorach dekoracyjnych oraz różnych zastosowaniach. Dzisiaj przyjrzymy się pochodzeniu, wyglądowi, a także możliwościom jego wykorzystania.
</p>

  <h2>Cedr syberyjski: pochodzenie</h2>
  <p style="text-align: justify">Pochodzenie cedru, z racji nazwy, nie powinno być dla nikogo zaskoczeniem. Jego naturalnym miejscem występowania jest zimna Syberia, choć rośnie on także na terenie Mongolii, Chin oraz w europejskiej części Rosji. W Polsce także można go spotkać, lecz wyłącznie w parkach i ogrodach — chętnie sadzi się cedr syberyjski z uwagi na wspomniane duże walory dekoracyjne.</p>




  <h2>Cedr syberyjski: wygląd</h2>
  <p style="text-align: justify">Cedr syberyjski potrafi osiągnąć do 35 metrów wysokości, choć w Polsce nie dorasta do takich rozmiarów. Młode gatunki drzew posiadają gładką, szarozieloną korę, która z czasem ciemnieje i zaczyna pękać. Zaglądając do wnętrza, możemy odkryć prawdziwe piękno — drewno w bogatej palecie kolorów: od białożółtego (najbardziej charakterystycznego) przez jasny bursztyn aż po ciemną czekoladę. Deski cedru syberyjskiego cechują się niezwykle bogatą fakturą, wyrazistym usłojeniem, a ich sęki są dużo większe niż w przypadku innych drzew, takich jak świerk.
</p>

<h2>Cedr syberyjski: zastosowanie
</h2>
 <p style="text-align: justify">Z racji swojego atrakcyjnego wyglądu i niezwykłych możliwości cedr syberyjski wykorzystywany był jako materiał budowlany już w czasach starożytnych. Wznoszono z niego gigantyczne budowle, pałace, a także wyposażano świątynie. Jego zastosowanie z zakresu budownictwa wiele się nie zmieniło na przestrzeni lat. Dzisiaj wciąż spore grono osób wznosi luksusowe domy z cedru syberyjskiego, łaźnie czy budynki wiejskie. To przede wszystkim zasługa właściwości drewna cedrowego, które na tle innych drzew iglastych wypada naprawdę korzystnie. Jest ono bowiem drewnem niezwykle trwałym — odpornym na zmiany temperatur i wilgotności. Niestraszne są mu silne mrozy czy upalne słońce. Wykonane z niego domy potrafią stać nawet przez setki lat.
</p>

<img class="post_image modrzew" src="../../static/cedrsyb2.jpg" alt="cedr syberyjski">
  <p style="text-align: justify">A to jeszcze nie wszystko, czym zachwyca cedr syberyjski. Drewno cedrowe jest przyjazne środowisku i ma korzystny wpływ na zdrowie. Ze względu na wysoką ilość wydzielanych fitoncydów cedr niszczy drobnoustroje chorobotwórcze, a tym samym oczyszcza powietrze wewnątrz domu. Ten niezwykły surowiec uwalnia też wspaniały aromat, znacznie bardziej intensywny niż inne drzewa. Ze względu na właściwości termoizolacyjne drewno z cedru syberyjskiego tworzy komfortowy mikroklimat.
</p>

<p style="text-align: justify">Zastosowanie cedru syberyjskiego jest jeszcze większe z uwagi na jego łatwą obróbkę. Drewno wykorzystuje się nie tylko do wznoszenia domów, ale też do tworzenia paneli podłogowych, a także przedmiotów codziennego użytku — ołówków, desek kreślarskich czy instrumentów muzycznych. Pozyskuje się z niego także olej o właściwościach leczniczych.</p>

<p style="text-align: justify">Cedr syberyjski to temat rzeka — co rusz zaskakuje nowymi właściwościami, czy to estetycznymi, czy praktycznymi. Nie da się w pełni przedstawić jego potencjału, lecz jednego jesteśmy pewni: drewno to może zostać wykorzystane niemal wszędzie i w każdym przypadku będzie prezentowało się doskonale. I tym pozytywnym akcentem kończymy naszą leśną przygodę. Do zobaczenia w kolejnych wpisach! ;-)</p>



</div>
    <the-footer></the-footer>
  </div>
</template>

<script>
import NavMenu from "../../components/nav/NavMenu.vue";
import TheFooter from "../../components/TheFooter.vue";

export default {head() {
    return {
      title: "Nauka nie pójdzie w las — charakterystyka cedru syberyjskiego | Forest Industry S.A.",
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
