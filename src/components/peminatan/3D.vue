<template>
  <!-- 3d -->
  <div class=" ">
    <p class="font-semibold text-5xl flex justify-center">
      3D
    </p>
    <div class="py-10">
      <p class=" font-medium text-lg">
        
      </p>
    </div>
  </div>
  <!-- start gallery -->
  <div class=" pt-16 justify-center flex pb-20 p-10">
    <div class="grid grid-cols-3 gap-20">
      <!-- rectangle1 -->
      <a href="https://drive.google.com/file/d/1SfVVILt0HYWtllcdyojh3AQhLVUVxc5-/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="../assets/3d1.jpg" alt="">
        </div>
      </a>
      <!-- rectagle 2 -->
      <a href="https://drive.google.com/file/d/1U0CRxZke9VwQp50Ah9yVuLcQ-2eLde0W/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="../assets/3d2.png" alt="">
        </div>
      </a>
      <!-- rectangle3 -->
      <a href="https://drive.google.com/file/d/1FAyiWZ66ZpDq87zt8Z6IaChn0uyYFfpZ/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="../assets/3d3.png" alt="">
        </div>
      </a>
      <!-- rectangle4 -->
      <a href="https://drive.google.com/file/d/112KM4e0M-CSKTMH3Hnrzxj0ZlnGBGUhB/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="../assets/3d4.png" alt="">
        </div>
      </a>
    </div>
  </div>
  <!-- end gallery -->
</template>

<script>
import gallery_row from '../gallery_db.vue';
export default {
  components: { gallery_row }
}
</script>
