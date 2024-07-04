<template></template>

<script setup>
const route = useRoute();

if (route.fullPath === "/") navigateTo("/cs2");
</script>
