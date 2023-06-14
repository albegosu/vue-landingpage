<template>
<section class="section-user">
      <h2>User Testimonials</h2>

      <!--Iconos Estrellas-->

      <div class="section-user__rick">
        <img class="section-user__rick__img" src="/src/assets/iconoEstrellasFix.png" alt="icono valoraciones" />
        <p class="section-user__rick__p">
          I love using Sync for my personal development needs. It meets all my
          requirements and it actually helps a lot with focusing skills.
        </p>
        <p class="section-user__rick__p"><strong>Rick Jones - Designer</strong></p>
      </div>

      <div class="section-user__lynda">
        <img class="section-user__lynda__img class=" src="/src/assets/iconoEstrellasFix.png" alt="icono valoraciones" />
        <p class="section-user__lynda__p">
          After trying out a large number of personal coaching apps I decided
          to give Sync a try and what a wonderful surprise it was.
        </p>
        <p class="section-user__lynda__p"><strong>Lynda Marquez - Developer</strong></p>
      </div>

      <div class="section-user__jay">
        <img class="section-user__jay__img" src="/src/assets/iconoEstrellasFix.png" alt="icono valoraciones" />
        <p class="section-user__jay__p">
          Never dreamed I could learn so fast how to focus on my personal
          goals and improve my life to levels I never thought possible.
        </p>
        <p class="section-user__jay__p"><strong>Jay Frisco - Marketer</strong></p>
      </div>

      <div class="section-user__customers">
        <img class="section-user__customers__img" src="/src/assets/customer-logo-1.png" alt="customer logo 1" />
        <img class="section-user__customers__img" src="/src/assets/customer-logo-2.png" alt="customer logo 2" />
        <img class="section-user__customers__img" src="/src/assets/customer-logo-3.png" alt="customer logo 3" />
        <img class="section-user__customers__img" src="/src/assets/customer-logo-4.png" alt="customer logo 4" />
        <img class="section-user__customers__img" src="/src/assets/customer-logo-5.png" alt="customer logo 5" />
      </div>

      <div class="section-user__frank">
        <img class="section-user__frank__img" src="src/assets/iconoEstrellasFix.png" alt="icono valoraciones" />
        <p class="section-user__frank__p">
          I got so much value from using Sync in my daily life for wich I am
          very grateful and would recommend it to everybody
        </p>
        <p class="section-user__frank__p"><strong>Frank Gibson - Manager</strong></p>
      </div>

      <div class="section-user__rita">
        <img class="section-user__rita__img" src="/src/assets/iconoEstrellasFix.png" alt="icono valoraciones" />
        <p class="section-user__rita__p">
          If you have great goals but can't figure out a way to keep focused
          then you should definitely give Sync a try and see the results
        </p>
        <p class="section-user__rita__p"><strong>Rita Longmile - Designer</strong></p>
      </div>

      <div class="section-user__jones">
        <img class="section-user__jones__img" src="/src/assets/iconoEstrellasFix.png" alt="icono valoraciones" />
        <p class="section-user__jones__p">
          I've been looking for a great organizer app for such a long time but
          now I am really happy that I found Sync. It's been working great
        </p>
        <p class="section-user__jones__p"><strong>Jones Smith - Developer</strong></p>
      </div>
    </section>
</template>

<style>
.section-user {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    background-color: #f7fafd;
}

.check-icon {
filter: invert(56%) sepia(95%) saturate(370%) hue-rotate(111deg)
    brightness(96%) contrast(93%);
}

.section-user {
    font-size: 16px;
}

.section-user p {
    width: 300px;
}

.section-user h2 {
    grid-column: 2;
    font-size: 2.75rem;
    margin: auto auto;
    padding-top: 20px;
}

.section-user__rick {
    grid-row: 2;
    width: 336px;
    height: 180px;
    text-align: center;
    padding-top: 50px;
margin: 0 auto;
}

.section-user__rick__p {
    margin: 0 auto;
    opacity: 0.7;
    padding-top: 20px;
}

.section-user__rick__img {
    width: 150px;
}

.section-user__lynda {
    grid-row: 2;
    grid-column: 2;
    width: 336px;
    height: 180px;
    text-align: center;
    padding-top: 50px;
    margin: 0 auto;
}

.section-user__lynda__p {
    margin: 0 auto;
    opacity: 0.7;
    padding-top: 20px;
}

.section-user__lynda__img {
    width: 150px;
}

.section-user__jay {
    grid-row: 2;
    width: 336px;
    height: 180px;
    text-align: center;
    padding-top: 50px;
    margin: 0 auto;
}

.section-user__jay__p {
    margin: 0 auto;
    opacity: 0.7;
    padding-top: 20px;
}

.section-user__jay__img {
    width: 150px;
}

.section-user__customers {
    display: flex;
    justify-content: center;
    width: 1110px;
    height: 111px;
    margin: 200px auto;
    align-items: center;
    grid-row: 3;
    grid-column: 1 / 4;
    background-color: #fff;
}

.section-user__customers__img {
    width: 175px;
    height: 35px;
    padding: 50px;
    background-color: #fff;
}

.section-user__frank {
    grid-column: 1;
    grid-row: 4;
    width: 336px;
    height: 180px;
    text-align: center;
    margin: 0 auto;
}

.section-user__frank__p {
    margin: 0 auto;
    opacity: 0.7;
    padding-top: 20px;
}

.section-user__frank__img {
    width: 150px;    
}

.section-user__rita {
    grid-column: 2;
    grid-row: 4;
    width: 336px;
    height: 180px;
    text-align: center;
    padding-bottom: 100px;
    margin: 0 auto;
}

.section-user__rita__p {
    margin: 0 auto;
    opacity: 0.7;
    padding-top: 20px;
}

.section-user__rita__img {
    width: 150px;
}

.section-user__jones {
    grid-row: 4;
    width: 336px;
    height: 180px;
    text-align: center;
    margin: 0 auto;
}

.section-user__jones__p {
    margin: 0 auto;
    opacity: 0.7;
    padding-top: 20px;
}

.section-user__jones__img {
    width: 150px;
}
</style>