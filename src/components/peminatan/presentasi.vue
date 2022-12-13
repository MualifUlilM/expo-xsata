<template>
  <!-- presentasi -->
  <div class="">
    <p class="font-semibold flex justify-center text-5xl">
      Presentasi
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
      <a href="https://drive.google.com/file/d/15GnCIJkHtgEz8c-BeYoFxImBKH1xuSzQ/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="../assets/pres1.jpg" alt="">
        </div>
      </a>
      <!-- rectagle 2 -->
      <a href="https://drive.google.com/file/d/1326bXiERS0lULz1_7zN6kxULjvhMF3z7/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="../assets/pres2.jpg" alt="">
        </div>
      </a>
      <!-- rectangle3 -->
      <a href="https://drive.google.com/file/d/1kZQoB7fHroQk0eM_77Odg2ZLh3gi5Qyz/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="../assets/pres3.jpg" alt="">
        </div>
      </a>
      <!-- rectangle4 -->
      <a href="https://drive.google.com/file/d/1JKx4yaacdY5sh-ZIjo4DyM8MPQdiRTp6/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="../assets/pres4.jpg" alt="">
        </div>
      </a>
      <!-- rectangle5 -->
      <a href="https://drive.google.com/file/d/1uSyt9aCX749_8fQS85g9zgCGQrK9msRc/view?usp=share_link" target="_blank">
        <div class="w-72 h-72 bg-slate-700 rounded-lg overflow-hidden">
          <img class="object-cover" src="../assets/pres5.jpg" alt="">
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
