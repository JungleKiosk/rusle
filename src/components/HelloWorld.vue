<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>
  <img width="20%" src="/src/assets/img/erosion.png" alt="">

  <h2>⚠️ Site Under Upgrade ⚠️</h2>

  <p>
    Dear users, <br>
    I am currently working on restoring the site to provide an improved experience and updated content. <br>
    My goal is to create a better understanding <br>of <strong>RUSLE analysis and modelling</strong> processes through
    ArcGIS Pro. <br><br>
    👉click <a href="https://github.com/JungleKiosk/rusle/blob/main/src/assets/pdf/Geotecnica_2022.pdf" target="_blank">HERE</a> to see and download a stability analysis paper using SSAP.
    <p>(if you download the pdf you can take advantage of the links in the table of contents)</p>
    <br>
    <img width="70%" src="/src/assets/img/github_pdf.png" alt="">
    <br>
    Thank you, <br>
    for your understanding.<br>
    For any urgent needs or information,<br>please do not hesitate to contact me at <br>
    <strong>email eso.fra24@gmail.com</strong> or
    at <strong>+39
      3311874661</strong>. <br>
    Thank you for your patience. <br>
    Kind regards, <br>
    Francesco</p>


  <div class="card">
    <button type="button" @click="count++">JS count test {{ count }}</button>
  </div>


</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
