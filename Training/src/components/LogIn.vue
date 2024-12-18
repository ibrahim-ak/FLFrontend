<template>
     <div class="flex items-center justify-center min-h-screen bg-stone-200">
          <div class="m-5 w-5/12 bg-white rounded-md">
               <div class="p-2 m-4">
                    <h1 class="text-sky-600 text-2xl font-bold">Log in</h1>
                    <p class="text-sky-600 pt-4">Enter Your Details Below To Continue</p>
               </div>
               <div class="p-4">
                    <input class="p-2 mb-4 ml-2 border-b w-6/12 focus:outline-none focus:border-blue-400" type="text" placeholder="Tenant Id">
                    <br>
                    <input class="p-2 mb-4 ml-2 border-b w-6/12 focus:outline-none focus:border-blue-400" type="text" placeholder="Username">
                    <br>
                    <input class="p-2 mb-4  ml-2 border-b w-6/12 focus:outline-none focus:border-blue-400" type="password" placeholder="Password">
               </div>
               <div class="ml-4">
                    <button class="p-2 m-2 mr-2 text-center w-7/12  border border-blue-400 rounded-md text-sky-600">Log In</button>
               </div>
               <div class="p-2 m-5 flex justify-between items-center mt-20 text-sky-600">
                    <p>Contact support </p>
                    <img src="../../flowless_water_logo.jpeg" width="60px" alt="flowless logo">
               </div>
          </div>
     </div>
</template>

<script setup lang="ts">

</script>

<style scoped></style>