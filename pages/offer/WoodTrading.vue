<template>
  <div>
    <nav-menu></nav-menu>
    <div>
      <h1 class="my-header">
        Handel drewnem tartacznym – świerk, modrzew, cedr syberyjski i inne
      </h1>
      <div class="content pcontent">
        <p style="text-align: justify">
          W naszej ofercie można znaleźć zarówno drzewo konstrukcyjne, tarasowe,
          jak i elewacyjne. Do sprzedania mamy deski tarasowe głównie z takiego
          drewna jak: sosna, modrzew, cedr oraz świerk syberyjski — nasz tartak
          proponuje je w mniejszych wymiarach od 2,5 m, przez średnie (np. 4 m
          lub 6 m) aż do 14 m. Dodatek do oferty stanowią natomiast takie
          gatunki jak: olcha, jesion, dąb czy buk. Nasze okrągłe drewno iglaste
          oraz liściaste oferujemy przede wszystkim firmom — jest to bowiem
          idealne drewno konstrukcyjne i budowlane do wznoszenia budynków czy
          wykonywania remontów. Nic jednak nie stoi na przeszkodzie, żeby drzewo
          tartaczne kupiły także osoby prywatne. To doskonały wybór na tarasy
          czy elewację.
        </p>

        <strong
          >Posiadamy w ofercie cenne gatunki drewna na sprzedaż, w tym:</strong
        >
        <ul style="margin-left: 40px">
          <li>świerk syberyjski,</li>
          <li>modrzew syberyjski,</li>
          <li>cedr syberyjski,</li>
          <li>sosna.</li>
        </ul>

        <strong>Okazjonalnie można u nas zakupić też takie drewno jak:</strong>

        <ul style="margin-left: 40px">
          <li>dąb</li>
          <li>buk,</li>
          <li>jesion,</li>
          <li>jawor,</li>
          <li>olcha.</li>
        </ul>

        <p style="text-align: justify">
          Każda nasza deska tarasowa bądź elewacyjna — czy to modrzewiowa,
          dębowa, jesionowa czy bukowa — jest teraz dostępna za niewielkie
          pieniądze. Cena jest ustalana zawsze indywidualnie na podstawie ilości
          zamówionego asortymentu. Stali klienci mają gwarancję, że materiały
          budowlane dotrą do nich przez cały rok. Dodatkowo mogą oni zamówić
          drewno w dowolnej ilości.
        </p>
        <h2>Skąd pochodzi nasze drewno?</h2>
        <p style="text-align: justify">
          Handel drewnem tartacznym rozpoczęliśmy już lata temu — wówczas
          sprzedawaliśmy nasze materiały lokalnie. Dzisiaj jesteśmy w stanie
          pochwalić się znacznym rozwojem, gdyż ludzie w całej Europie
          wykorzystują drewno na elewację i do remontów. Aby usprawnić sprzedaż
          drewna tartacznego, uruchomiliśmy kilka składnic za granicami kraju —
          sprowadzamy m.in. drewno tartaczne z Czech oraz Słowacji. Ceny drewna
          w Czechach są znacznie niższe niż w innych krajach, dlatego też handel
          jest bardziej opłacalny.
        </p>
        <p style="text-align: justify">
          Jeśli więc planują Państwo wykonać elewację bądź taras drewniany z
          modrzewia syberyjskiego, świerku, sosny czy innego cennego gatunku
          drewna, zachęcamy do kontaktu. Dysponujemy takimi materiałami jak
          kantówka, tarcica czy deska gładka — z nami mogą Państwo kupić drewno
          z Czech, ze Śląska i Słowacji oraz wykorzystać je do różnych celów,
          np. przeznaczyć na elegancką i trwałą elewację.
        </p>

        Handlujemy drewnem wyłącznie posiadającym certyfikaty PEFC oraz
        FSC&reg;.
      </div>
    </div>
    <div class="row, myrow">
      <footer class="col the-footer">
        &copy; 2022 Forest Industry S.A.: Handel drewnem tartacznym – świerk,
        modrzew syberyjski inne <br />
        All rights reserved.
        <a
          href="https://www.facebook.com/Forest-Industry-SA-108708038192828"
          target="_blank"
          ><i class="fa fa-facebook-square" style="color: #4267b2"></i
        ></a>
      </footer>
    </div>
  </div>
</template>

<script>
import NavMenu from "../../components/nav/NavMenu.vue";
// import TheFooter from "../../components/TheFooter.vue";

export default {
  head() {
    return {
      title:
        "Handel drewnem syberyjskim: świerk, sosna i inne | Forest Industry S.A.",
      meta: [
        {
          name: "description",
          content:
            "Kup cenne gatunki drewna w atrakcyjnej cenie! W naszej ofercie świerk, sosna, modrzew i wiele więcej. Sprzedajemy drewno konstrukcyjne i tarasowe.",
        },
      ],
    };
  },
  components: {
    NavMenu,
  },
};
</script>

<style>
.my-header {
  margin-top: 3rem;
  text-align: center;
  font-family: "Merriweather", serif;
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

.pcontent {
  max-width: 75% !important;
}

@media (max-width: 1028px) {
  .content {
    max-width: 90%;
  }

  .pcontent {
    max-width: 90% !important;
  }
}

.the-footer {
  position: fixed !important;
  bottom: 0;
  font-family: "Libre Baskerville", serif;
  text-align: center;
  font-weight: bold;
  width: 100%;
  font-size: 1rem;
  background: rgb(136, 158, 129);
  padding: 0.5rem;
}

i {
  font-size: 1.1rem !important;
  background-color: inherit;
  margin-left: 0.5%;
}

.myrow {
  margin-left: 0 !important;
}
</style>
