<template>
  <!-- programing -->
  <div class="">
    <p class="font-semibold text-5xl flex justify-center">
      Programming
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
      <a href="#">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="" alt="">
        </div>
      </a>
      <!-- rectagle 2 -->
      <a href="#">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="" alt="">
        </div>
      </a>
      <!-- rectangle3 -->
      <a href="#">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="" alt="">
        </div>
      </a>
      <!-- rectangle4 -->
      <a href="#">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="" alt="">
        </div>
      </a>
      <!-- rectangle5 -->
      <a href="#">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="" alt="">
        </div>
      </a>
      <!-- rectagle6 -->
      <a href="#">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="" alt="">
        </div>
      </a>
      <!-- rectangle7 -->
      <a href="#">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="" alt="">
        </div>
      </a>
      <!-- rectangle8 -->
      <a href="#">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="" alt="">
        </div>
      </a>
      <!-- rectangle9 -->
      <a href="#">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="" alt="">
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
