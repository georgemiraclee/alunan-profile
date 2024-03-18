<template>
    <div class="flex items-center flex-col md:flex-row flex-grow" id="custom_rounded">
        <div data-aos="fade-left" data-aos-duration="1000" class="m-10 md:m-5">
                <img
                :src="'/img/illustrator.png'"
                class="md:object-scale-down"
                />
          </div>
          <div data-aos="fade-up" data-aos-duration="1000" class="m-10 md:m-5">
            <p class="text-white font-thin ">11 Oktober 2021</p>
            <p class="text-4xl md:text-5xl lg:text-6xl font-bold text-yellow-400">Belajar Adobe Illustrator</p>
            <p class="text-white font-thin ">Author</p>
            <p class="text-white font-medium ">Noval</p>
          </div>
    </div>  
</template>

<script>
export default {};
</script>

<style>
#custom_rounded {
  border-bottom-right-radius: 200px;
  height: 600px;
  background: rgb(255, 207, 51);
  background: linear-gradient(
    90deg,
    rgb(250, 250, 250) 0%,
    rgb(250, 249, 249) 100%
  );
}
</style>