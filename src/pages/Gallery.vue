<template>
  <container-component>
      <title-page-component>
      <template v-slot:title-page>Galeri</template>
      <template v-slot:keterangan>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</template>
    </title-page-component>
    <div class="flex flex-wrap">
        <div data-aos="fade-left" data-aos-duration="1000" class="w-full">
        <ul class="grid grid-cols-1 md:grid-cols-3 list-none gap-5 m-10">
            <li class="w-full mx-auto text-center">
            <a class="text-3xl font-semibold p-3 shadow-lg rounded-2xl block leading-normal" v-on:click="toggleTabs(1)" v-bind:class="{'text-gray-600 bg-white border-2': openTab !== 1, 'text-white bg-gray-600': openTab === 1}">
                EVENT
            </a>
            </li>
            <li class="w-full mx-auto text-center">
            <a class="text-3xl font-semibold p-3 shadow-lg rounded-2xl block leading-normal" v-on:click="toggleTabs(2)" v-bind:class="{'text-gray-600 bg-white border-2': openTab !== 2, 'text-white bg-gray-600': openTab === 2}">
                EVENT 1
            </a>
            </li>
            <li class="w-full mx-auto text-center">
            <a class="text-3xl font-semibold p-3 shadow-lg rounded-2xl block leading-normal" v-on:click="toggleTabs(3)" v-bind:class="{'text-gray-600 bg-white border-2': openTab !== 3, 'text-white bg-gray-600': openTab === 3}">
                EVENT 2
            </a>
            </li>
        </ul>
        <div class="flex flex-col">
            <div class="w-full">
            <div class="tab-content tab-space">
                <div v-bind:class="{'hidden': openTab !== 1, 'block': openTab === 1}">
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-2 mx-auto">
                        <div data-aos="fade-left" data-aos-duration="1500">
                            <img :src="'/img/galeri.jpg'" class="h-96 w-96 object-cover object-center rounded-3xl my-2"/>
                        </div>
                        <div data-aos="fade-left" data-aos-duration="1700">
                            <img :src="'/img/galeri.jpg'" class="h-96 w-96 object-cover object-center rounded-3xl my-2" />
                        </div>
                        <div data-aos="fade-left" data-aos-duration="1900">
                            <img :src="'/img/galeri.jpg'" class="h-96 w-96 object-cover object-center rounded-3xl my-2" />
                        </div>
                        <div data-aos="fade-left" data-aos-duration="2100">
                            <img :src="'/img/galeri.jpg'" class="h-96 w-96 object-cover object-center rounded-3xl my-2" />
                        </div>
                        <div data-aos="fade-left" data-aos-duration="2300">
                            <img :src="'/img/galeri.jpg'" class="h-96 w-96 object-cover object-center rounded-3xl my-2" />
                        </div>
                        <div data-aos="fade-left" data-aos-duration="2500">
                            <img :src="'/img/galeri.jpg'" class="h-96 w-96 object-cover object-center rounded-3xl my-2" />
                        </div>
                    </div>
                </div>
                <div v-bind:class="{'hidden': openTab !== 2, 'block': openTab === 2}">
                    <p>event 1</p>
                </div>
                <div v-bind:class="{'hidden': openTab !== 3, 'block': openTab === 3}">
                    <p>event 2</p>
                </div>
            </div>
            </div>
        </div>
        </div>
    </div>

  </container-component>
  <footer-component />
</template>

<script>
import ContainerComponent from '../components/ContainerComponent.vue';
import FooterComponent from "../components/FooterComponent.vue";
import NavBar from "../components/NavBar.vue";
import TitlePageComponent from "../components/TitlePageComponent.vue";

export default {
    name: "gray-tabs",
  data() {
    return {
      openTab: 1
    }
  },
  methods: {
    toggleTabs: function(tabNumber){
      this.openTab = tabNumber
    }
  },
    components: {
  NavBar,
  ContainerComponent,
  FooterComponent,
  TitlePageComponent,
  },
}
</script>

<style>

</style>