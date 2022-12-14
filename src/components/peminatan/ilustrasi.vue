<template>
  <!-- illustrasi -->
  <div class="">
    <p class="font-semibold text-5xl flex justify-center">
      Illustrasi
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
      <!-- <a href="https://drive.google.com/file/d/1REBZkuXSnW_LZ6a6nrK4uiM0joC-RqHh/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="../assets/ilus1.jpg" alt="">
        </div>
      </a> -->
      <!-- rectagle 2 -->
      <a href="https://drive.google.com/file/d/1Dz27_RANENwYc3TXwd1FzXE5aquBcZPJ/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="../assets/ilus2.jpg" alt="">
        </div>
      </a>
      <!-- rectangle3 -->
      <a href="https://drive.google.com/file/d/1rJJaw2FfwUSmITi2brwN9Iq7peYjPLP8/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="../assets/ilus3.jpg" alt="">
        </div>
      </a>
      <!-- rectangle4 -->
      <!-- <a href="https://drive.google.com/file/d/1B9l-4nQsGEwq9gfQkooqUf-mRsm3EUKO/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="../assets/ilus4.jpg" alt="">
        </div>
      </a> -->
      <!-- rectangle5 -->
      <a href="https://drive.google.com/file/d/1GMGfYBhCoiQtsw3oyC7L0M29yi-vxQZu/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="../assets/ilus5.jpg" alt="">
        </div>
      </a>
      <!-- rectagle6 -->
      <a href="https://drive.google.com/file/d/1SMeXJFRZm_kjnYXld-5iHRJ39Ruzkhrv/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="../assets/ilus6.jpg" alt="">
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
