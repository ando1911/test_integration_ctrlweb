<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/layout/Header.vue'
</script>

<template>
    <div class="container mx-auto mb-2">
        <Header />
        <RouterView />
    </div>
</template>