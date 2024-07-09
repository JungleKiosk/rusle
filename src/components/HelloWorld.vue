<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <h2>⚠️ Site under Upgrade ⚠️</h2>

  <p>
    Dear users, <br>
    I am currently working on restoring the site to provide an improved experience and updated content. <br>
    My goal is to create a better understanding <br>of <strong>RUSLE analysis and modelling</strong> processes through
    ArcGIS Pro. <br>
    Thank you
    for your understanding and continued support. <br>
    For any urgent needs or information,<br>please do not hesitate to contact me at email eso.fra24@gmail.com or
    at +39
    3311874661. <br>
    Thank you for your patience. <br>
    Kind regards, <br>
    Francesco</p>


  <div class="card">
    <button type="button" @click="count++">count test {{ count }}</button>
  </div>


</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
