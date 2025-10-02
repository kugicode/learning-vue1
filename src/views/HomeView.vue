<script setup>
import Hero from './Hero.vue';
import HomeCards from './HomeCards.vue';
import JobListings from './JobListings.vue';
</script>

<template>
    <Hero  />
    <HomeCards />
    <JobListings :limit="3" :show-button="true"/>
    
</template>