<template>
<div class="container mx-auto">
  <div class="navbar flex mb-4 w-auto text-left h-16">
    <div class="w-1/2 px-2 py-2">
        <router-link to="/">
        <img src = "../assets/Logo-UT_03.png">
        </router-link>
    </div>
    <div class="w-1/2 flex py-5">
        <div class="mr-3 w-1/8">
            <router-link to="/about" class="text-blue-500 py-1 px-3">About UT</router-link>
        </div>
        <div class="mr-5 w-1/8 text-blue-500">
            <div class="">Akademik</div>
        </div>
        <div class="mr-5 w-1/8 text-blue-500">
            <div class="">UT Online</div>
        </div>
        <div class="mr-5 w-1/8 text-blue-500">
            <div class="">Fasilitas</div>
        </div>
        <div class="mr-5 w-1/8 text-blue-500">
            <div class="">Berita</div>
        </div>
        <div class="mr-10 w-1/8 text-blue-500">
            <div class="">Pengumuman</div>
        </div>
        <div class="w-1/8 text-blue-500 font-semibold">
            <div class="">Masuk</div>
        </div>
        <router-view/>
    </div>
  </div>
</div>
</template>


<style scoped>

</style>