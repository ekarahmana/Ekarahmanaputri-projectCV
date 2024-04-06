<template>
<navbar />
 <home/>
 <about/>
 <skill/>
 <footers />
</template>

<script setup>
import navbar from "./components/navbar.vue"
import home from "./views/HomeView.vue"
import about from "./views/AboutView.vue"
import skill from "./views/SkillView.vue"
import footers from "./components/footer.vue"
</script>
