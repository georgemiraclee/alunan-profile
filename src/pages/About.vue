<template>
  <container-component>
    <div class="flex items-center flex-col md:flex-row flex-grow">
      <div data-aos="fade-left" data-aos-duration="1000">
        <img :src="'/img/logo.png'" class="md:object-scale-down" />
      </div>
      <div data-aos="fade-up" data-aos-duration="1000" class="w-4/5 m-10 md:m-5">
        <p class="text-4xl font-bold">SEJARAH ALUNAN</p>
        <div class="border-b-2 border-blue-400 h-2 w-20 mt-2 mb-5"></div>
        <br>
        <p class="justify-text-stretch">Alunan adalah sebuah komunitas sosial non-profit yang bergerak di bidang kesenian. Komunitas ini dibentuk untuk seluruh alumni FLS2N SMA di Indonesia dan Sekolah Indonesia Luar Negeri (SILN) agar terjalin ikatan yang solid, terus berkarya dan berkesenian. Hal itu pula 
          yang menjadi langkah preventif untuk melestarikan budaya Indonesia yang beragam.
        </p>
      </div>
    </div>
  </container-component>
  <container-component>
    <div data-aos="fade-up" data-aos-duration="1000">
        <p class="text-5xl font-bold mt-10 text-center">VISI</p>
        <div class="border-b-2 border-blue-400 h-2 w-20 mt-2 mx-auto mb-5 "></div>
        <p class="text-center">Rumah bagi seniman muda nusantara dalam mengembangkan seni dan melestarikan  budaya Indonesia.</p>
      </div>
  </container-component>
  <container-component>
    <div data-aos="fade-up" data-aos-duration="1000">
        <p class="text-5xl font-bold mt-10 text-center">MISI</p>
        <div class="border-b-2 border-blue-400 h-2 w-20 mt-2 mx-auto mb-5"></div>
        <p class="text-center">Menghimpun alumni FLS2N dalam komunitas Alunan.</p>
        <p class="text-center">Mempersiapkan & memberdayakan para talenta seni sesuai dengan talentanya.</p>
        <p class="text-center">Berkontribusi dengan pegiat seni budaya.</p>
      </div>
  </container-component>
  <footer-component />
</template>

<script>
import ContainerComponent from '../components/ContainerComponent.vue';
import FooterComponent from "../components/FooterComponent.vue";
import NavBar from "../components/NavBar.vue";

export default {
  components: {
  NavBar,
  ContainerComponent,
  FooterComponent,
  },
};
</script>

<style>

</style>