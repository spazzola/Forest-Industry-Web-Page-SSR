<template>
  <div>
    <nav-menu></nav-menu>
    <div class="content">
  
  <h1>Dom z bali — dlaczego stał się tak popularny?</h1>
<img class="post_image" src="../../static/domzbali.jpg" alt="domy z bali">
  <p style="text-align: justify">Domy z bali to ciekawa propozycja architektoniczna i choć kojarzy się z zabudowaniami na wsiach oraz w rejonach górskich, to coraz więcej osób się na nie decyduje. Powstają one na przedmieściach, a także w małych miasteczkach. Budowa domu z bali drewnianych to świetny sposób na uzyskanie atrakcyjnie wyglądającego i komfortowego budynku. Będzie on trwały, a postawić go można w o wiele krótszym czasie niż typowy dom murowany. Oczywiście ogromną rolę odgrywa tu dobór odpowiedniego budulca — polecany cedr syberyjski to najwyższej jakości materiał do budowy domu z bali.</p>

  <h2>Jak jest skonstruowany dom z bali drewnianych?</h2>
  <p style="text-align: justify">Obecnie stosuje się dwa rodzaje konstrukcji, które różnią się między sobą grubością użytych bali drewnianych, sposobem ich układania, łączenia oraz izolowania. Wyróżniamy budowę z bali cienkich, które wymagają zastosowania dodatkowej warstwy ocieplenia. Z zewnątrz będzie widoczna drewniana elewacja , a w środku montuje się płyty gipsowo kartonowe, które zakrywają drewno — będą one doskonałą bazą pod farbę, czy też tapetę. Natomiast budując z bali pełnych, docieplenie nie jest już wymagane. Taki dom powstaje z licznych bali drewnianych, układanych na siebie poziomo — tworząc tzw. wieniec po całym obrysie budynku. Tego typu budynki nie wymagają wykończenia od wewnątrz — drewniane bale same w sobie wyglądają bardzo atrakcyjnie. W takim wnętrzu doskonale będą się czuć miłośnicy sielskich oraz rustykalnych klimatów.</p>

  <h2>Skąd jego popularność?</h2>
  <p style="text-align: justify">W przeciwieństwie do domów murowanych najważniejszą cechą, jaką posiadają takie domy, to kumulowanie ciepła i regulacja wilgotności. O praktyczności domów z bali świadczy również fakt, że są ocieplone w sposób naturalny. Drewno jest świetnym izolatorem termicznym, latem pochłania ciepło z zewnątrz, pozostawiając wnętrze domu przyjemnie chłodne, natomiast zimą ciepło zostaje oddane, chroniąc przed zbytnim wychłodzeniem. Oprócz tego dom wykonany w takiej technologii jest uznawany za mający dobry wpływ na zdrowie — świetnie radzi sobie z wilgocią w pomieszczeniach, dzięki czemu tworzy bardzo korzystny mikroklimat dla mieszkańców, a niesprzyjający dla rozwoju mikroorganizmów takich jak pleśnie i grzyby. Czynnikiem, który równie często jest brany pod uwagę przez osoby, które decydują się na dom z bali, jest stosunkowo krótki czas budowy. Dzięki temu, że budynek nie wymaga żadnych prac mokrych, można go wznosić nawet zimą, na przygotowanym wcześniej fundamencie.</p>

 <p style="text-align: justify"> Dom z bali stanowi doskonałą alternatywę dla technologii murowanej. Jeszcze kilka lat temu kojarzył się on z domkiem letniskowym — klimatycznym miejscem do wypoczynku na łonie natury. Dziś dzięki swojemu urokowi i zaletom, jakie posiada, sprawia, że ludzie coraz chętniej decydują się na jego budowę. Całoroczne domy z bali można spotkać w wielu regionach naszego kraju.</p>



</div>
    <the-footer></the-footer>
  </div>
</template>

<script>
import NavMenu from "../../components/nav/NavMenu.vue";
import TheFooter from "../../components/TheFooter.vue";

export default {head() {
    return {
      title: "Dom z bali - dlaczego stał się tak popularny? | Forest Industry S.A.",
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

@media(max-width: 600px) {
  .post_image{
    max-width: 300px;
  }

  .content {
    max-width: 90%;
  }
}
</style>
