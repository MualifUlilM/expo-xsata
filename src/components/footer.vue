<template>
      <!-- footer -->
      <footer class="bg-[#0cb0a9] py-8">
    <!-- flex container -->
    <div class="container flex flex-col-reverse justify-between px-6 mx-auto space-y-7 md:flex-row md:space-y-0">
        <!-- logo and sosial links container -->
        <router-link to="/">
            <div class="flex flex-col-reverse items-center justify-between my-9 space-y-12 md:flex-col md:space-y-0 md:items-start">
                <!-- logo -->
                <div class="absolute flex-row flex">
                <img class="h-10 my-5 ml-14" src="../components/assets/smk.png" alt="">
                <img class="h-12 my-4 ml-8" src="../components/assets/logoka.png" alt="">
                </div>
            </div>
        </router-link>
        <!-- list container -->
        <div class="flex justify-around gap-x-36 pr-10">
            <div class="flex flex-col space-y-3 text-black">
                <p class="font-semibold hover:text-white"><router-link to="/programing">Programming</router-link></p>
                <p class="font-semibold hover:text-white"><router-link to="/3D">3D</router-link></p>
                <p class="font-semibold hover:text-white"><router-link to="/ilustrasi">Ilustrasi</router-link></p>
                <p class="font-semibold hover:text-white"><router-link to="/presentasi">Presentasi</router-link></p>
            </div>
            <div class="flex flex-col space-y-3 text-black">
                <p class="font-semibold hover:text-white"><router-link to="/about">About</router-link></p>
                <p class="font-semibold hover:text-white"><router-link to="/">Gallery</router-link></p>
            </div>
        </div>
    </div>
  </footer>
</template>

<script>

</script>