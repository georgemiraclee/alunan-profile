<template>
  <container-component>
    <div class="text-center">
      <p data-aos="fade-down" data-aos-duration="1000" class="text-4xl font-bold mb-10">Event Yang Akan Datang</p>
    </div>
    <div class="bg-abucoklat rounded-3xl" data-aos="zoom-in-down" data-aos-duration="1000">
      <div class="grid grid-cols-3 p-7">
        <div class="col-span-3 md:col-span-1 flex items-center justify-center">
          <div
            class="
              h-64
              w-64
              p-5
              rounded-3xl
              shadow-2xl
              flex
              justify-center
              items-center
            "
            id="card-logo"
          >
            <img :src="'/img/logo.png'" class="w-full p-3" />
          </div>
        </div>
        <div class="ml-3 col-span-3 md:col-span-2">
          <div class="grid grid-rows-3 h-full">
            <div class="row-span-2 text-white">
              <div class="flex items-center h-full">
                <div>
                  <p class="font-medium text-3xl text-center md:text-left mt-5 md:mt-0">AMI (Alunan Memanggil Indonesia)</p>
                  <p class="font-light mt-2 leading-6">
                    Alunan Menyapa Indonesia [AMI] adalah sebuah progran dari alunan yang hadir untuk memberikan ruang diskusi kepada para 
                    calon peserta dan para medalis bidang-bidang lomba FLS2N untuk bertukar 
                    ilmu, pengalaman, dan tips menjadi juara.
                  </p>
                </div>
              </div>
            </div>
            <div class="row-span-1">
              <button
                id="btn-card"
                class="
                  font-bold
                  px-6
                  py-4
                  mt-2
                  rounded-2xl
                  border-2
                  custom-btn-border
                  text-blue-400
                "
              >
                Selengkapnya
              </button>
            </div>
          </div>
        </div>
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
#card-logo {
  background-color: rgb(255, 207, 51)
}

.custom-btn-border {
  border-color: rgb(255, 207, 51)
}
</style>