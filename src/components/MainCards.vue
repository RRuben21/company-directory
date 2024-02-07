<script setup>
import MaincardSingle from './MaincardSingle.vue/';
</script>


<template>

<MaincardSingle v-for = "card in 20" :key="card"></MaincardSingle>

</template>