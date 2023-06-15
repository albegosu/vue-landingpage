<script setup>
  import Button from '../components/ButtonComponent.vue';
</script>

<template>     
    <section class="section-bottom">
      <div class="section-bottom__image">
        <img id="phone-image-bottom" src="/src/assets/download-iphone.png" alt="imagen fondo 4" />
      </div>
      <div class="section-bottom__container">
      <p class="section-bottom__container__p">
        Do you feel like you're wasting time with small stuff instead of
        working towards your goals? Start using Sync to organize your time and
        get a grip on your personal development
      </p>

      <div class="button-download">
        <Button>
          <template #svg>
            <svg class="button-download__icon" xmlns="http://www.w3.org/2000/svg"
              width="30" height="30" viewBox="0 0 24 24"
              stroke-width="1.5" stroke="none" fill="#ffff" stroke-linecap="round" stroke-linejoin="round">
              <path stroke="none" d="M0 0h24v24H0z" fill="none" />
              <path
                d="M9 7c-3 0 -4 3 -4 5.5c0 3 2 7.5 4 7.5c1.088 -.046 1.679 -.5 3 -.5c1.312 0 1.5 .5 3 .5s4 -3 4 -5c-.028 -.01 -2.472 -.403 -2.5 -3c-.019 -2.17 2.416 -2.954 2.5 -3c-1.023 -1.492 -2.951 -1.963 -3.5 -2c-1.433 -.111 -2.83 1 -3.5 1c-.68 0 -1.9 -1 -3 -1z" />
              <path d="M12 4a2 2 0 0 0 2 -2a2 2 0 0 0 -2 2" />
            </svg>
          </template>
          <template #nameBtn>
            Download
          </template>
        </Button>
        <Button>
          <template #svg>
            <svg class="button-download__icon" xmlns="http://www.w3.org/2000/svg"
             width="30" height="30" viewBox="0 0 24 24"
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
    </div>
    </section>
</template>

<style scoped>
.section-bottom {
    padding-top: 100px;
    padding-bottom: 100px;
}
.section-bottom__image {
    display: flex;
    justify-content: center;
}
#phone-image-bottom {
    width: 968px;
    height: 580px;
    padding-top: 100px;
}
.section-bottom__container {
    text-align: center;
}
.section-bottom__container__p {
    width: 50%;
    margin: 0 auto;
}
.button-download {
    display: flex;
    justify-content: center;
    margin-top: 50px;
}
</style>