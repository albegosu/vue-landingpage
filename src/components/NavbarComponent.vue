<script setup>
  import { RouterLink, RouterView } from "vue-router";
  import Button from "../components/ButtonComponent.vue";
</script>

<template>
  <header>
    <div>
      <RouterLink to="/">
        <img src="/src/assets/logo.svg" id="top-icon" alt="Logo">
      </RouterLink>
    </div>
    <nav>
      <ul class="top-menu">
        <li><RouterLink to="">Description</RouterLink></li>
        <li><RouterLink to="">Features</RouterLink></li>
        <li><RouterLink to="">Screens</RouterLink></li>
        <li class="dropdown">
          <RouterLink to="">Extra</RouterLink>
          <div class="dropdown-content">
            <RouterLink to="">Article Details</RouterLink>
            <RouterLink to="">Terms Conditions</RouterLink>
            <RouterLink to="">Privacy Policy</RouterLink>
          </div>
        </li>
        <li>
          <RouterLink to="/login">
            <Button class="button-download__button">
              <template #nameBtn>Login</template>
            </Button>
          </RouterLink>
        </li>
      </ul>
    </nav>
  </header>
  <RouterView />
</template>

<style scoped>
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0 3rem;
    gap: auto;
}
nav {
  display: flex;
  flex-direction: column;
}

#top-icon {
  width: 5rem;
}

li:nth-child(1) {
  display: none;
}

li:nth-child(2){
  display: none;
}

li:nth-child(3){
  display: none;
}

@media (min-width: 800px) {
  header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0 3rem;
    gap: auto;
  }
  #top-icon {
      width: 6.7rem;
  }
  nav {
      width: 70%;
  }
  li:nth-child(1) {
  display: block;
  }

  li:nth-child(2){
    display: block;
  }

  li:nth-child(3){
    display: block;
  }
}
.button-download__button {
  color: #ff556e !important;
  background-color: white !important;
}
.button-download__button:hover {
  background-color: #ff556e !important;
  color: white !important;;
}
.top-menu li {
    list-style: none;
    margin: 0 10px;
    text-transform: uppercase;
    font-family: 'Open sans', sans-serif;
    font-weight: 700;
}
a {
    text-decoration: none;
    color: #000000;
}
.top-menu {
    display: flex;
    justify-content: flex-end;
    align-items: center;
}
.dropdown {
    display: inline-block;
    position: relative;
}
.dropdown-content {
    display: none;
    position: absolute;
    overflow: auto;
    box-shadow: 0px 10px 15px 0px rgba(0, 0, 0, 0.4);
    padding: 5px;
    z-index: 5;
}
.dropdown:hover .dropdown-content {
    display: block;
    white-space: nowrap;
}
.dropdown-content a {
    display: block;
    color: #000000;
    padding: 5px;
    text-decoration: none;
}
.dropdown-content a:hover {
    color: #ff556e;
}
.top-menu a:hover{
    color: #ff556e;
}

</style>