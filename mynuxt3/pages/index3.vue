<template>

    <div class="w-80 border-0 border-gray-400 p-2 flex flex-col gap-2">
        <div class="flex justify-center">
            <img class="border-0 border-red-600 w-48 " :src="logo_url">
        </div>
        <div class="font-bold p-2 text-justify">{{ topic }}</div>
        <div class=" p-2 text-justify">Internationalize MSME operations <div class="font-bold inline">to meet international standards and practices</div> by aligning MSME operation procedures and support systems towards AACSB and EdPEx standards, as well as increasing deployment of international practices in teaching and learning.</div>                
        <div class=" p-2 text-right"><NuxtLink to="/">read more...</NuxtLink></div>
    </div>
</template>

<script setup lang="ts">
var logo_url = 'https://www.msme.au.edu/wp-content/uploads/2020/11/logo.png';
var topic = 'Strengthening Education Quality towards International Standards.';

</script>

<style scoped>

</style>