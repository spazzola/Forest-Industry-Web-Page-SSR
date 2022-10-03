<template>
  <div>
    <nav-menu></nav-menu>
    <div class="page_offer">
      <header class="page_header wood">
        <h1 class="page_heading flex" style="align-items: center">
          Handel węglem – ekogroszek
        </h1>
      </header>

      <div class="container-fluid offer">
        <div class="width_container">
          <div class="row">
            <div class="col-lg-4 col-md-6">
              <img
                class="section_image"
                src="../../static/coal2.jpg"
                alt="handel drewnem"
              />
            </div>
            <div class="col-lg-8 col-md-6 flex">
              <p>
                W naszej ofercie można również znaleźć węgiel typu ekogroszek. Importowany przez nas surowiec cechuje się
                najwyższą kalorycznością.
              </p>
              <p>
                <strong
                  >Posiadamy w ofercie gramaturę:</strong
                >
              </p>
              <ul style="margin-left: 40px">
                <li>0-25,</li>
                <li>4-25,</li>
                <li>3-50,</li>
                <li>3-60.</li>
              </ul>
              <p>
                
              <p>
                Oferowany przez nas węgiel jest pakowany w big-bagach 1000kg. Na życzenie klienta oferujemy załadunek kupionego towaru.
              </p>
            </div>
          </div>
        </div>
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
        "Węgiel ekogroszek | Forest Industry S.A.",
      meta: [
        {
          name: "description",
          content:
            "Kup najwyszej jakości węgiel typu ekogroszek w atrakcyjnej cenie!",
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

.page_offer {
  padding-bottom: 200px;
}
.page_offer * {
  background-color: transparent !important;
}

.page_header {
  background-image: url("../../static/coal1.jpg");
  background-position: bottom;
  background-size: cover;
  width: 100vw;
  height: 650px;
}

.page_header.wood {
  background-image: url("../../static/coal1.jpg");
}

.flex {
  display: flex;
  justify-content: center;

  flex-direction: column;
}

.page_heading {
  margin: 0;
  padding: 0;
  background-color: rgba(255, 255, 255, 0.4) !important;
  height: 100%;
  width: 100%;

  color: white;
  text-shadow: 3px 3px #000;
}

.page_offer p {
  font-weight: 500;
  text-align: justify;
}

.width_container {
  max-width: 80%;
  margin: 0 auto;
  padding-left: 15px;
}

.container-fluid.offer {
  margin-top: 80px;
}

.section_image {
  width: 100%;
}

.section_heading {
  align-self: flex-start;
}

.gallery {
  background-color: rgb(136, 158, 129) !important;
}

.gallery img {
  margin: 25px 0;
}
.background_image {
  background-image: url("../../static/loghome1.jpg");
  background-size: cover;
  background-position: center;
}

.contact_button {
  display: block;
  margin: 0 auto;
  text-align: center;
  background-color: rgb(136, 158, 129) !important;
  width: 150px;
  padding: 10px 0;
  color: black;
  text-transform: uppercase;
  font-weight: bold;
  transition: 0.3s;
  font-size: 16px;
}
.contact_button:hover {
  color: white !important;
  background-color: rgb(71 82 68) !important;
}

@media (max-width: 1150px) {
  .width_container {
    max-width: 95%;
    margin: 0 auto;
  }
}
</style>
