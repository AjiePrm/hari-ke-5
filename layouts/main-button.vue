<template>
    <button class=" fancy-btn inline-flex text-white border-0 py-2 px-6 focus:outline-none bg-red-400 hover:bg-red-600 rounded text-lg">
        Learn more
        <slot/>
    </button>
     <!-- required here only -->
</template>

<script setup>
    definePageMeta({
        layout: "main-button"
    })
</script>

<style >

</style>