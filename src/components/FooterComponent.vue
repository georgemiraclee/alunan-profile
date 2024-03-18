<template>
  <div id="footer-rounded" class="relative">
    <container-component>
      <div class="grid grid-cols-4 text-white h-full">
        <div class="col-span-4 md:col-span-1 flex items-center justify-center h-full">
          <div>
            <img :src="'/img/logo.png'" class="w-28 md:w-48 mt-5 md:mt-0 mx-auto md:mx-0" />
            <p class="mt-14 font-medium text-xl md:text-2xl">Alamat</p>
            <p class="text-sm md:text-base">Jl. Jenderal Sudirman No.19, RT.1/RW.3,  Jakarta Pusat, Jakarta</p>
          </div>
        </div>
        <div class="col-span-4 md:col-span-1 pt-2 md:pt-24">
          <div>
            <p class="font-medium text-2xl mb-4">Informasi</p>
            <div class="font-light">
              <p class="my-1">Tentang Kami</p>
              <p class="my-1">Artikel</p>
              <p class="my-1">Galeri</p>
            </div>
          </div>
          </div>
        <div class="col-span-4 md:col-span-1 pt-2 md:pt-24">
          <div>
            <p class="font-medium text-2xl mb-4">Kontak Kami</p>
            <div class="font-light">
              <p class="my-1">Email : alunan.fls2n@gmail.com</p>
            </div>
          </div>
        </div>
        <div class="col-span-4 md:col-span-1 pt-2 md:pt-24">
          <p class="font-medium text-2xl mb-2">Sosial Media</p>
          <div class="px-4 flex items-center">
              <a
                href="https://instagram.com/alunanfls2n"
                target="_blank"
                class="w-9 h-9 mr-3 rounded-full flex justify-center items-center border border-slate-300 text-white bg-red-600 lg:hover:bg-white lg:hover:text-red-600 transition-all duration-200 ease-in-out"
              >
                <svg
                  class=" fill-current"
                  width="20"
                  role="img"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <title>Instagram</title>
                  <path
                    d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913.306.788.717 1.459 1.384 2.126.667.666 1.336 1.079 2.126 1.384.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558.788-.306 1.459-.718 2.126-1.384.666-.667 1.079-1.335 1.384-2.126.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913-.306-.789-.718-1.459-1.384-2.126C21.319 1.347 20.651.935 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227-.224.562-.479.96-.899 1.382-.419.419-.824.679-1.38.896-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421-.569-.224-.96-.479-1.379-.899-.421-.419-.69-.824-.9-1.38-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678c-3.405 0-6.162 2.76-6.162 6.162 0 3.405 2.76 6.162 6.162 6.162 3.405 0 6.162-2.76 6.162-6.162 0-3.405-2.76-6.162-6.162-6.162zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405c0 .795-.646 1.44-1.44 1.44-.795 0-1.44-.646-1.44-1.44 0-.794.646-1.439 1.44-1.439.793-.001 1.44.645 1.44 1.439z"
                  />
                </svg>
              </a>
              <a
                href="https://www.youtube.com/@smkn4tanjungpinang751"
                target="_blank"
                class="w-9 h-9 mr-3 rounded-full flex justify-center items-center border border-slate-300 text-white bg-yellow-400 lg:hover:bg-white lg:hover:text-yellow-400 transition-all duration-200 ease-in-out"
              >
                <svg
                  class="fill-current"
                  xmlns="http://www.w3.org/2000/svg"
                  height="25"
                  viewBox="-35.20005 -41.33325 305.0671 247.9995"
                >
                  <path
                    d="M93.333 117.559V47.775l61.334 34.893zm136.43-91.742c-2.699-10.162-10.651-18.165-20.747-20.881C190.716 0 117.333 0 117.333 0S43.951 0 25.651 4.936C15.555 7.652 7.603 15.655 4.904 25.817 0 44.236 0 82.667 0 82.667s0 38.429 4.904 56.849c2.699 10.163 10.65 18.165 20.747 20.883 18.3 4.934 91.682 4.934 91.682 4.934s73.383 0 91.683-4.934c10.096-2.718 18.048-10.72 20.747-20.883 4.904-18.42 4.904-56.85 4.904-56.85s0-38.43-4.904-56.849"
                  />
                </svg>
              </a>
              <a
                href="https://www.linkedin.com/company/alunanfls2n/mycompany/"
                target="_blank"
                class="w-9 h-9 mr-3 rounded-full flex justify-center items-center border border-slate-300 text-white bg-blue-600 lg:hover:bg-white lg:hover:text-green-600 transition-all duration-200 ease-in-out"
              >
                <svg
                  class="currentcolor"
                  width="16"
                  height="16"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 16 16"
                >
                  <path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854V1.146zm4.943 12.248V6.169H2.542v7.225h2.401zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248-.822 0-1.359.54-1.359 1.248 0 .694.521 1.248 1.327 1.248h.016zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016a5.54 5.54 0 0 1 .016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225h2.4z"  fill="white"
                  />
                </svg>
              </a>
            </div>
        </div>
      </div>
      <div class="absolute bottom-4 text-white w-full text-center">
        ©2023 | AlunanFls2n
    </div>
    </container-component>
  </div>
</template>

<script>
import ContainerComponent from "./ContainerComponent.vue";

export default {
  components: {
    ContainerComponent,
  },
};
</script>

<style>
.router-link-active {
  border-bottom: 2px solid rgb(255, 192, 56);
}

#footer-rounded {
  border-top-left-radius: 250px;
  height: 400px;
  background: rgba(255, 220, 20, 0.863);
  background: linear-gradient(
    90deg,
    rgba(2, 0, 36, 1) 0%,
    rgba(10, 10, 10, 1) 0%,
    rgba(67, 68, 68, 1) 50%
  );
}

@media only screen and (max-width: 800px) {
  #footer-rounded {
    border-top-left-radius: 150px;
    height: 800px;
    background: rgb(2, 0, 36);
    background: linear-gradient(
      90deg,
      rgba(67, 68, 68, 1) 0%,
      rgba(10, 10, 10, 1) 100%
    );
  }
  
}
</style>