<script setup>
  import NavbarComponent from "./components/icons/NavbarComponent.vue"
  import ImagePhoneComponent from "./components/icons/ImagePhoneComponent.vue"
  import ContainerMiddle from "./components/icons/ContainerMiddle.vue"
  import Organize from "./components/icons/Organize.vue"
  import CalendarComponent from "./components/icons/CalendarComponent.vue"
  import User from "./components/icons/User.vue"
  import Numbers from "./components/icons/Numbers.vue"
  import ButtonComponent from "./components/icons/ButtonComponent.vue"
  import FooterComponent from "./components/icons/FooterComponent.vue"
</script>

<template>
  <NavbarComponent />
  <ImagePhoneComponent />
  <ContainerMiddle />
  <Organize />
  <CalendarComponent />
  <User />
  <Numbers />
  <ButtonComponent />
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
}


/* .button-terms {
    background-color: #ff556e;
    color: #fff;
    border-radius: 28px;
    border: 2px solid #ff556e;
    font-size: 14px;
    font-weight: 700;
    width: 100px;
    height: 50px;
}

.button-privacy {
    background-color: #e8eff6;
    border: 2px solid #000;
    border-radius: 28px;
    width: 100px;
    height: 50px;
    font-size: 14px;
    font-weight: 700;
}

.container-buttons__privacy {
    margin-bottom: 50px;
}

.button-terms:hover {
    background-color: #ebe7fa;
    border: 2px solid #ff556e;
    color: #ff556e;
    transition: all 0.2s;
}

.button-privacy:hover {
    background-color: #000000;
    color: #ebe7fa;
    transition: all 0.2s;
}
 */

</style>
