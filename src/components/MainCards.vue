<script setup>
import MainCardsSingle from '@/components/MainCardsSingle.vue'
</script>

<template>
    <div class="sub-wrapper">
        <MainCardsSingle v-for="n in 16" :key="n"/>
    </div>
</template>

<style scoped lang="postcss">
    .sub-wrapper{
        @apply ml-5 mr-5 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-4 ; 
    }
</style>