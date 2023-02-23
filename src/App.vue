<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './layout/HelloWorld.vue'
import './style.css'
import headersection from './layout/headersection.vue'
import contentsection from './layout/contentsection.vue'
import footersection from './layout/footersection.vue'
</script>

<template>
<headersection></headersection>
<RouterView></RouterView>
<footersection></footersection>
</template>

