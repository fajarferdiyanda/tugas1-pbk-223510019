<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      Nama : Fajar Ferdiyanda <br />
      Tempat/Tanggal Lahir : Pekanbaru/29 Agustus 2003 <br />
      Jurusan : Teknik Informatika <br />
      Pendidikan : Universitas Islam Riau <br />
      Tahun Masuk : 2022 <br />

      <a href="https://vitejs.dev/" target="_blank" rel="noopener"></a>
      <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
  color: black;
}

h3 {
  font-size: 1.2rem;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  color: white;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
