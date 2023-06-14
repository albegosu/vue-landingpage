<script setup>
  import { RouterLink, RouterView } from "vue-router";
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
          <RouterLink to="/login"><button class="button-download__top">Login</button></RouterLink>
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
.button-download__top {
    -webkit-border-radius: 28px;
    -moz-border-radius: 28px;
    border-radius: 1.75rem;
    border: 2px solid #ff556e;
    padding: 5px 20px;
    color: var(--button-color);
    text-transform: uppercase;
    font-size: 0.875rem;
    font-family: 'Open sans', sans-serif;
    background-color: #fff;
    font-weight: 700;
}
.button-download__top:hover {
    background-color: #ff556e;
    color: white;
    transition: all 0.4s;
}
.top-menu {
    display: flex;
    justify-content: flex-end;
    align-items: baseline;
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