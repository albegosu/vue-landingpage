<template>
    <section class="container-middle">
      <div class="container-icons-middle">
        <div class="container-icons-middle__icon">
          <img class="container-icons-middle__img" src="/src/assets/usersIconFix.png" alt="Users icon" />
          <p class="icons-middle__text">Identify Goals</p>
        </div>

        <div class="container-icons-middle__icon">
          <img class="container-icons-middle__img" src="/src/assets/keyIconFix.png" alt="Keys icon" />
          <p class="icons-middle__text">Situation Analysis</p>
        </div>

        <div class="container-icons-middle__icon">
          <img class="container-icons-middle__img" src="/src/assets/gearIconFix.png" alt="gear icon" />
          <p class="icons-middle__text">Tasks Settings</p>
        </div>

        <div class="container-icons-middle__icon">
          <img class="container-icons-middle__img" src="/src/assets/messageIconFix.png" alt="message icon" />
          <p class="icons-middle__text">Social Interaction</p>
        </div>

        <div class="container-icons-middle__icon">
          <img class="container-icons-middle__img" src="/src/assets/rocketIconFix.png" alt="rocket icon" />
          <p class="icons-middle__text">Get Things Done</p>
        </div>
      </div>
    </section>
</template>

<style scoped>
.container-icons-middle {
    display: flex;
    justify-content: space-evenly;
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
}
</style>