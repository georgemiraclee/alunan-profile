<template>
  <div class="relative" id="custom_rounded">
    <div class="grid grid-cols-1 md:grid-cols-2 h-full">
      <div class="flex items-center">
        <div class="mx-10 lg:mx-24">
          <p data-aos="fade-down" data-aos-duration="1000" class="text-4xl md:text-5xl lg:text-6xl font-bold text-blue-400">
            Selamat Datang di Wadah Seniman Nusantara
          </p>
          <p data-aos="fade-right" data-aos-duration="1000" class="mt-5 text-black font-light ">
            Wadah para seniman muda Indonesia untuk terus mengembangkan bakat dan talenta serta
             kolaborasi guna melestarikan kesenian dan kebudayaan Indonesia.
          </p>
        </div>
      </div>
      <div></div>
    </div>
    <img data-aos="fade-left" data-aos-duration="1000" data-aos-delay="300"
      :src="'/img/alunan_header.png'"
      class="
        h-2/5
        md:h-2/4
        lg:h-4/5
        absolute
        bottom-0
        right-14
        mr-0
        md:mr-20
        lg:mr-40
      "
    />
  </div>
</template>

<script>
export default {};
</script>

<style>
@media only screen and (max-width: 800px) {
  #custom_rounded {
    border-bottom-right-radius: 100px !important;
    height: 600px;
    background: rgb(67, 68, 68);
    background: linear-gradient(
      90deg,
      rgba(67, 68, 68, 1) 0%,
      rgba(10, 10, 10, 1) 100%
    );
  }
}
</style>