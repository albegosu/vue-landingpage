<script setup>
    import Button from '../components/ButtonComponent.vue';
</script>

<template>
  <section class="section-organize">
      <div class="section-organize__img">
        <img id="organize-image" src="/src/assets/description-1-app.png" alt="imagen fondo 1" />
      </div>
      <div class="section-organize__content">
        <h2 id="organize-title">Organize Your Time And Start Getting Results</h2>
        <p>
          Sync is the first mobile app on the market to harness the power of
          social connections to help you stop procrastinating and start
          getting things done. Give it a try and see the changes right away
        </p>

        <ul>
          <li>Analyse and evaluate your current status and productivity</li>
          <li>Begin monitoring your day to day routine with Sync app</li>
          <li>See the improved results in no more than a couple of weeks</li>
        </ul>
        <Button class="button-download__button">
          <template #nameBtn>LIGHTBOX</template>
        </Button>
      </div>
    </section>
</template>

<style>
.section-organize {
    display: flex;
    justify-content: space-around;
    margin-bottom: 100px;
}

.section-organize__img img {
    width: 497px;
    height: 586px;
}

.section-organize__content {
    width: 580px;
    height: 586px;
    margin-top: 5rem;
    margin-left: 2.5rem;
    justify-content: center;
}

.section-organize__content p {
    line-height: 30px;
    font-size: 16px;
    opacity: 0.7;
}

.section-organize__content ul {
    line-height: 40px;
    padding: 15px;
    list-style: square;
    opacity: 0.6;
}

#organize-title {
    font-size: 40px;
    margin-bottom: 1.5rem;
}
</style>