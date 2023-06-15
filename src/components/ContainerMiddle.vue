<template>
    <section class="container-middle">
      <div class="container-icons-middle">
        <div class="container-icons-middle__icon">
          <img class="container-icons-middle__img" src="/src/assets/usersIconFix.png" alt="Users icon" />
          <p class="icons-middle__text"><strong>Identify Goals</strong></p>
        </div>

        <div class="container-icons-middle__icon">
          <img class="container-icons-middle__img" src="/src/assets/keyIconFix.png" alt="Keys icon" />
          <p class="icons-middle__text"><strong>Situation Analysis</strong></p>
        </div>

        <div class="container-icons-middle__icon">
          <img class="container-icons-middle__img" src="/src/assets/gearIconFix.png" alt="gear icon" />
          <p class="icons-middle__text"><strong>Tasks Settings</strong></p>
        </div>

        <div class="container-icons-middle__icon">
          <img class="container-icons-middle__img" src="/src/assets/messageIconFix.png" alt="message icon" />
          <p class="icons-middle__text"><strong>Social Interaction</strong></p>
        </div>

        <div class="container-icons-middle__icon">
          <img class="container-icons-middle__img" src="/src/assets/rocketIconFix.png" alt="rocket icon" />
          <p class="icons-middle__text"><strong>Get Things Done</strong></p>
        </div>
      </div>
    </section>
</template>

<style scoped>
.container-icons-middle {
    display: flex;
    gap: 100px;
}

.container-icons-middle__img {
    align-self: center;
    width: 65px;
    height: 65px;
    margin: 0 auto;
    padding-top: 30px;
}

.container-icons-middle__icon {
    display: flex;
    width: 120px;
    height: 120px;
    flex-direction: column;
    background-color: #ebe7fa;
    border-radius: 50%;

}

.container-middle {
    margin-top: 50px;
    margin-bottom: 200px;
    display: flex;
}

.icons-middle__text {
  align-self: center;
  margin-top: 27%;
  text-align: center;
}

@media (max-width: 768px) {
  .container-icons-middle {
    gap: 10px;
    flex-direction: column;
  }

  .container-icons-middle__icon {
    width: auto;
    height: auto;
  }

  .container-icons-middle__img {
    width: 45px;
    height: 45px;
    padding-top: 20px;
  }

  .icons-middle__text {
    margin-top: 20%;
  }
}
</style>