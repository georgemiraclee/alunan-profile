<template>
  <container-component>
    <title-page-component>
      <template v-slot:title-page>Artikel Terbaru</template>
      <template v-slot:keterangan
        >Berikut merupakan artikel terbaru seputar berita Monster
        Binary</template
      >
    </title-page-component>
    <div class="flex flex-wrap justify-center md:justify-between items-center gap-10" data-aos="fade-up">
      <artikel-card-component>
        <template v-slot:artikel-title><router-link to="/dasarIllustrator">Belajar Adobe Illustrator</router-link></template>
        <template v-slot:artikel-teks
          >#1. Dasar - dasar tools Adobe Illustrator</template
        >
        <template v-slot:artikel-gambar
          ><img :src="'/img/illustrator.png'"
        /></template>
      </artikel-card-component>
      <artikel-card-component>
        <template v-slot:artikel-title><router-link to="/dasarPhotoshop">Belajar Adobe Photoshop</router-link></template>
        <template v-slot:artikel-teks>#1. Dasar - dasar tools Adobe Photoshop</template>
        <template v-slot:artikel-gambar><img :src="'/img/photoshop.png'"/></template>
      </artikel-card-component>
      <artikel-card-component>
        <template v-slot:artikel-title><router-link to="/sketchingIllustrator">Belajar Adobe Illustrator</router-link></template>
        <template v-slot:artikel-teks
          >#2. Membuat sketching logo di Adobe Illustrator</template
        >
        <template v-slot:artikel-gambar
          ><img :src="'/img/illustrator.png'"
        /></template>
      </artikel-card-component>
      <artikel-card-component>
        <template v-slot:artikel-title><router-link to="/pentoolPhotoshop">Belajar Adobe Photoshop</router-link></template>
        <template v-slot:artikel-teks
          >#2. Cara menggunakan pen tool yang baik dan benar di Adobe
          Photoshop</template
        >
        <template v-slot:artikel-gambar
          ><img :src="'/img/photoshop.png'"
        /></template>
      </artikel-card-component>
    </div>
  </container-component>
  <footer-component />
</template>

<script>
import ContainerComponent from "../components/ContainerComponent.vue";
import FooterComponent from "../components/FooterComponent.vue";
import NavBar from "../components/NavBar.vue";
import ArtikelCardComponent from "../components/NewsComp/ArtikelCardComponent.vue";
import TitlePageComponent from "../components/TitlePageComponent.vue";

export default {
  components: {
    NavBar,
    ContainerComponent,
    ArtikelCardComponent,
    FooterComponent,
    TitlePageComponent,
  },
};
</script>

<style>
</style>