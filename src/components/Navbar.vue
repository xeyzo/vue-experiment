<template>
  <div class="navbar flex mb-4 w-auto text-left h-16">
    <div class="w-1/2 px-2 bg-red-200 py-5">
        <router-link to="/">Rumah-Sandi</router-link>
    </div>
    <div class="w-1/2 flex bg-red-100 py-5">
        <div class="mr-3 w-1/8">
            <router-link to="/" class="w-1/2 hover:border-gray-200 text-blue-500 hover:bg-gray-200 py-1 px-3">Home</router-link>
        </div>
        <div class="mr-3 w-1/8">
            <router-link to="/about" class="hover:border-gray-200 text-blue-500 hover:bg-gray-200 py-1 px-3">About</router-link>
        </div>
         <div class="mr-3 w-1/8 bg-text-right">
            <h1>ini</h1>
        </div>
        <router-view/>
    </div>
  </div>
</template>


<style scoped>

</style>