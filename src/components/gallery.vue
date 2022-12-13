<template>
  <!-- judul -->
  <div class="flex justify-center pt-20 pb-5">
    <p class="text-5xl font-extrabold">
      Our Gallery
    </p>
  </div>
  <!-- start gallery -->
  <div class=" pt-16 justify-center flex p-10 pb-10">
    <div class="grid grid-cols-3 gap-20">
      <!-- rectangle1 -->
      <a href="https://drive.google.com/file/d/1SfVVILt0HYWtllcdyojh3AQhLVUVxc5-/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="./assets/3d1.jpg" alt="">
        </div>
      </a>
      <!-- rectagle 2 -->
      <a href="https://drive.google.com/file/d/1U0CRxZke9VwQp50Ah9yVuLcQ-2eLde0W/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="./assets/3d2.png" alt="">
        </div>
      </a>
      <!-- rectangle3 -->
      <a href="https://drive.google.com/file/d/1FAyiWZ66ZpDq87zt8Z6IaChn0uyYFfpZ/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="./assets/3d3.png" alt="">
        </div>
      </a>
      <!-- rectangle4 -->
      <a href="https://drive.google.com/file/d/112KM4e0M-CSKTMH3Hnrzxj0ZlnGBGUhB/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="./assets/3d4.png" alt="">
        </div>
      </a>
      <!-- rectangle5 -->
      <a href="https://drive.google.com/file/d/1REBZkuXSnW_LZ6a6nrK4uiM0joC-RqHh/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="./assets/ilus1.JPG" alt="">
        </div>
      </a>
      <!-- rectagle6 -->
      <a href="https://drive.google.com/file/d/1Dz27_RANENwYc3TXwd1FzXE5aquBcZPJ/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="./assets/ilus2.jpg" alt="">
        </div>
      </a>
      <!-- rectangle7 -->
      <a href="https://drive.google.com/file/d/1rJJaw2FfwUSmITi2brwN9Iq7peYjPLP8/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="./assets/ilus3.jpg" alt="">
        </div>
      </a>
      <!-- rectangle8 -->
      <a href="https://drive.google.com/file/d/1B9l-4nQsGEwq9gfQkooqUf-mRsm3EUKO/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="./assets/ilus4.jpg" alt="">
        </div>
      </a>
      <!-- rectangle9 -->
      <a href="https://drive.google.com/file/d/1GMGfYBhCoiQtsw3oyC7L0M29yi-vxQZu/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="./assets/ilus5.jpg" alt="">
        </div>
      </a>
      <a href="https://drive.google.com/file/d/1SMeXJFRZm_kjnYXld-5iHRJ39Ruzkhrv/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="./assets/ilus6.jpg" alt="">
        </div>
      </a>
      <a href="https://drive.google.com/file/d/15GnCIJkHtgEz8c-BeYoFxImBKH1xuSzQ/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="./assets/pres1.jpg" alt="">
        </div>
      </a>
      <a href="https://drive.google.com/file/d/1326bXiERS0lULz1_7zN6kxULjvhMF3z7/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="./assets/pres2.jpg" alt="">
        </div>
      </a>
      <a href="https://drive.google.com/file/d/1kZQoB7fHroQk0eM_77Odg2ZLh3gi5Qyz/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="./assets/pres3.jpg" alt="">
        </div>
      </a>
      <a href="https://drive.google.com/file/d/1JKx4yaacdY5sh-ZIjo4DyM8MPQdiRTp6/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="./assets/pres4.jpg" alt="">
        </div>
      </a>
      <a href="https://drive.google.com/file/d/1uSyt9aCX749_8fQS85g9zgCGQrK9msRc/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="./assets/pres5.jpg" alt="">
        </div>
      </a>
    </div>
  </div>
  <!-- end gallery -->
</template>
  
<script>
import gallery_row from './gallery_db.vue';
export default {
  components: { gallery_row }
}
</script>
  