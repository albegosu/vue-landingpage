<template>
   <section class="section-numbers">
      <div class="section-numbers__container section-numbers__users">
        <img src="/src/assets/usersIconFix.png" alt="users icon" />
        <p class="section-numbers__container__number">231</p>
        <p>Happy Users</p>
      </div>

      <div class="section-numbers__container section-numbers__keys">
        <img src="/src/assets/keyIconFix.png" alt="keys icon" />
        <p class="section-numbers__container__number">385</p>
        <p>Issues Solved</p>
      </div>

      <div class="section-numbers__container section-numbers__gear">
        <img src="/src/assets/gearIconFix.png" alt="gear icon" />
        <p class="section-numbers__container__number">159</p>
        <p>Good Reviews</p>
      </div>

      <div class="section-numbers__container section-numbers__messages">
        <img src="/src/assets/messageIconFix.png" alt="messages icon" />
        <p class="section-numbers__container__number">127</p>
        <p>Case Studies</p>
      </div>

      <div class="section-numbers__container section-numbers__rocket">
        <img src="/src/assets/rocketIconFix.png" alt="rocket icon" />
        <p class="section-numbers__container__number">211</p>
        <p>Orders Received</p>
      </div>
    </section>
</template>

<style scoped>

.section-numbers {
    display: flex;
    justify-content: center;
    background-color: #e8eff6;
    padding: 60px;
}

.section-numbers__container {
    text-align: center;
    font-size: 16px;
    margin-left: 50px;
    margin-right: 50px;
}

.section-numbers__container img {
    width: 60px;
    height: 60px;
}

.section-numbers__container__number {
    font-size: 2rem;
    font-weight: 700;
    opacity: 0.8;
}
</style>
