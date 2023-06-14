<script setup>
  import NavbarComponent from "./components/NavbarComponent.vue"
  import FooterComponent from "./components/FooterComponent.vue"
</script>

<template>
    <NavbarComponent />
   
    <FooterComponent />
</template>

<style scoped>
:root {
    --background-color: #fff;
    --button-color: #ff556e;
    --main-font: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
}

body{
    background-color: #f7fafd;
    font-family: 'Open sans', sans-serif;
    display: block;
}
</style>
