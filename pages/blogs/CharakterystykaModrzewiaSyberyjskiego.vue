<template>
  <div>
    <nav-menu></nav-menu>
    <div class="content">
  
  <h1>Nauka nie pójdzie w las — charakterystyka modrzewia syberyjskiego</h1>
<img class="post_image modrzew" src="../../static/modrzew.jpg" alt="modrzew syberyjski">
  <p style="text-align: justify">Modrzew syberyjski od lat podbija serca osób aranżujących własny taras czy altankę. Jego popularność wzrosła, kiedy architekci zaczęli wykorzystywać ten gatunek drewna również do tworzenia domów z bali. Nie bez powodu właśnie to on stał się hitem sprzedaży i zapoczątkował naszą nową serię wpisów: „Nauka nie pójdzie w las”. Dziś przyjrzyjmy się jego specyfice.</p>

  <h2>Modrzew syberyjski: pochodzenie</h2>
  <p style="text-align: justify">Gatunek ten, jak sama nazwa wskazuje, pochodzi z Syberii. Nie jest to jednak jego jedyne miejsce występowania. Modrzew syberyjski rośnie również w Chinach i Mongolii. Skrajne warunki atmosferyczne Azji sprawiły, że ten gatunek wykształcił w sobie niebywałą odporność na mróz. Jest to drewno niezwykle twarde, osiągające wysokość nawet do 45 metrów.</p>

  <h2>Modrzew syberyjski: wygląd</h2>
  <p style="text-align: justify">Deski z modrzewia syberyjskiego charakteryzują się bogatą barwą kolorystyczną. Jest to z reguły jasne drewno, naturalnie występujące w kolorze złocistomiodowym oraz w atrakcyjnej barwie czerwonobrunatnej lub żółto-pomarańczowej. Piękna kolorystyka modrzewia syberyjskiego sprawia, że jest to gatunek łatwy do zaaranżowania w wielu przestrzeniach. Należy jednak zwrócić uwagę, że w przypadku naturalnego drewna każda z desek będzie inna, a więc cała kompozycja nie będzie jednolita pod względem usłojenia. To z kolei dodaje oryginalnego charakteru naszej aranżacji.</p>

<h2>Modrzew syberyjski: zastosowanie</h2>
 <p style="text-align: justify">Drewno z modrzewia syberyjskiego znalazło zastosowanie w wielu sektorach budownictwa. Najpopularniejsze są przede wszystkim domy z bali modrzewia syberyjskiego. Budynek wykonany z tego gatunku drewna doskonale sprawdzi się jako miejsce do całorocznego zamieszkania. Dobrym wyborem będzie też elewacja z modrzewia syberyjskiego — nie tylko stylowa, ale i wytrzymała. Drewno można wykorzystać również na podbitki dachowe, deski podłogowe, tarasy, altany czy płoty. Nic nie stoi na przeszkodzie, by z modrzewia wykonać także oryginalne meble do domu lub ogrodu.</p>
  <p style="text-align: justify">Krótkim słowem podsumowania — modrzew syberyjski to ekskluzywne, a przy tym wytrzymałe drewno, które wpasuje się niemal wszędzie. Jest odporne na działanie niskich temperatur, występowanie grzybów i pleśni. Jest również wyjątkowe ze względu na prosty, niekiedy lekko spleciony układ włókien, różnice w usłojeniu oraz ciekawą kolorystykę. Należy mieć jednak na uwadze, że mimo swoich właściwości, modrzew syberyjski jest drewnem naturalnym, które należy odpowiednio czyścić i pielęgnować. W tym celu warto wykorzystywać oleje do drewna, a także dedykowane środki chemiczne do desek drewnianych.</p>



</div>
    <the-footer></the-footer>
  </div>
</template>

<script>
import NavMenu from "../../components/nav/NavMenu.vue";
import TheFooter from "../../components/TheFooter.vue";

export default {head() {
    return {
      title: "Nauka nie pójdzie w las — charakterystyka modrzewia syberyjskiego | Forest Industry S.A.",
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
