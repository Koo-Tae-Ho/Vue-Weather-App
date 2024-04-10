<template>
    <div class="container">
        <SearchBar />
        <WeatherInfo />
    </div>
</template>

<script setup>
import WeatherInfo from "./WeatherInfo.vue";
import SearchBar from "./SearchBar.vue";
</script>

<style lang="scss" scoped>
.container {
    padding: 20px;
}
</style>
