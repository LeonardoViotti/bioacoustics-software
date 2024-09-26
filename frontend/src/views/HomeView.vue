<script setup lang="ts">
import DataTable from "../components/DataTable.vue";
</script>
<!--  TODO: use the createLink function -->
<template>
    <div class="flow-root">  
        <!-- <img class="h-auto max-w-xs float-left" src=".././assets/BiocAI_image.png" width=100 alt="Logo of the BiocAI project"> -->
        <!-- <img class="h-auto  max-w-xs rounded-lg float-right" src=".././assets/EU.png" width=90 alt="EU flag"> -->
    </div>
    <div class="text-center mb-4">
        <h1 class="about text-center mb-4 mt-4 text-4xl font-extrabold">Bioacoustics Software</h1>
        <p>This table presents publicly available bioacoustics software.</p>
    </div>
    <DataTable></DataTable>
</template>