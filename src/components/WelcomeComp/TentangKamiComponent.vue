<template>
  <container-component>
    <div class="md:grid grid-cols-6">
      <div data-aos="fade-right" data-aos-duration="1000" class="col-span-6 md:col-span-2 flex items-center justify-start">
        <div class="bg-abucoklat h-72 w-72 p-5 rounded-3xl shadow-2xl flex justify-center items-center">
          <img :src="'/img/logo.png'" class="w-full p-3" />
        </div>
      </div>
      <div data-aos="fade-left" data-aos-duration="1000" class="col-span-4 mr-0 md:mr-10 ml-5">
        <p class="text-4xl font-bold mt-10">Tentang Kami</p>
        <p class="mt-5 leading-7">Alunan adalah sebuah komunitas sosial non-profit yang bergerak di bidang kesenian. Komunitas ini dibentuk untuk seluruh alumni FLS2N SMA sederajat di Indonesia</p>
        <router-link to="/about"><button id="btn-custom" class="text-white font-bold px-6 py-4 mt-16 rounded-2xl">Selengkapnya</button></router-link>
      </div>
    </div>
  </container-component>
</template>

<script>
import ContainerComponent from "../ContainerComponent.vue";

export default {
  components: {
    ContainerComponent,
  },
};
</script>
<style>
#btn-custom {
  background-color: #f0c33c;
  box-shadow: #f0c33c 0px 7px 29px 0px;
}
</style>
