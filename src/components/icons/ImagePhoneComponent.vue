<script setup>
  import Button from "./Button.vue"
</script>

<template>
  <section>
      <div class="mobile-landing">
        <h1 class="mobile-landing__title">Mobile App Landing Page</h1>
        <p class="mobile-landing__p">
          Start focusing on your goals and get more things done with Sync
          mobile application. It's the first app to harness the power of
          social connections to help stay focused and get organized
        </p>
      </div>

      <div class="button-download">
        <Button>
          <template #svg>
            <svg class="button-download__icon" xmlns="http://www.w3.org/2000/svg"
              width="44" height="44" viewBox="0 0 24 24"
              stroke-width="1.5" stroke="none" fill="#ffff" stroke-linecap="round" stroke-linejoin="round">
              <path stroke="none" d="M0 0h24v24H0z" fill="none" />
              <path
                d="M9 7c-3 0 -4 3 -4 5.5c0 3 2 7.5 4 7.5c1.088 -.046 1.679 -.5 3 -.5c1.312 0 1.5 .5 3 .5s4 -3 4 -5c-.028 -.01 -2.472 -.403 -2.5 -3c-.019 -2.17 2.416 -2.954 2.5 -3c-1.023 -1.492 -2.951 -1.963 -3.5 -2c-1.433 -.111 -2.83 1 -3.5 1c-.68 0 -1.9 -1 -3 -1z" />
              <path d="M12 4a2 2 0 0 0 2 -2a2 2 0 0 0 -2 2" />
            </svg>
          </template>
          <template #nameBtn>
            Miguel
          </template>
        </Button>
        <Button>
          <template #svg>
            <svg class="button-download__icon" xmlns="http://www.w3.org/2000/svg"
             width="44" height="44" viewBox="0 0 24 24"
            stroke-width="1.5" stroke="#ff556e" fill="#fff" stroke-linecap="round" stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
            <path
              d="M4 3.71v16.58a.7 .7 0 0 0 1.05 .606l14.622 -8.42a.55 .55 0 0 0 0 -.953l-14.622 -8.419a.7 .7 0 0 0 -1.05 .607z" />
            <path d="M15 9l-10.5 11.5" />
            <path d="M4.5 3.5l10.5 11.5" />
          </svg>
          </template>
          <template #nameBtn>
            Download
          </template>
        </Button>
      </div>
    </section>

    <div class="container-image-phone">
      <img class="phone-image" src="src/assets/header-iphone.png" alt="iphone header" />
    </div>
</template>

<style scoped>
.mobile-landing {
    justify-content: center;
    text-align: center;
}

h1 {
    text-align: center;
    font-size: 64px;
    opacity: 0.8;
}

.mobile-landing__p {
    width: 60%;
    text-align: center;
    font-weight: 550;
    opacity: 0.6;
    justify-content: center;
    margin: 0px auto 2rem auto ;
}

.container-image-phone {
    display: flex;
    justify-content: center;
}

.phone-image {
    width: 929px;
    margin-top: 50px;
}

.phone-image:hover {
    transform: scale(1.2);
    transition: all 0.2s;
}
</style>