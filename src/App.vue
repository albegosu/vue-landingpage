<script setup>
  import NavbarComponent from "./components/icons/NavbarComponent.vue"
  import ImagePhoneComponent from "./components/icons/ImagePhoneComponent.vue"
  import FooterComponent from "./components/icons/FooterComponent.vue"
</script>

<template>
  <NavbarComponent />
  <ImagePhoneComponent />
  <FooterComponent />

  <main>
    

    <section class="container-middle">
      <div class="container-icons-middle">
        <div class="container-icons-middle__icon">
          <img class="container-icons-middle__img" src="images/usersIconFix.png" alt="Users icon" />
          <p class="icons-middle__text">Identify Goals</p>
        </div>

        <div class="container-icons-middle__icon">
          <img class="container-icons-middle__img" src="images/keyIconFix.png" alt="Keys icon" />
          <p class="icons-middle__text">Situation Analysis</p>
        </div>

        <div class="container-icons-middle__icon">
          <img class="container-icons-middle__img" src="images/gearIconFix.png" alt="gear icon" />
          <p class="icons-middle__text">Tasks Settings</p>
        </div>

        <div class="container-icons-middle__icon">
          <img class="container-icons-middle__img" src="images/messageIconFix.png" alt="message icon" />
          <p class="icons-middle__text">Social Interaction</p>
        </div>

        <div class="container-icons-middle__icon">
          <img class="container-icons-middle__img" src="images/rocketIconFix.png" alt="rocket icon" />
          <p class="icons-middle__text">Get Things Done</p>
        </div>
      </div>
    </section>
    <section class="section-organize">
      <div class="section-organize__img">
        <img id="organize-image" src="images/description-1-app.png" alt="imagen fondo 1" />
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
        <button class="lightbox-button">LIGHTBOX</button>
      </div>
    </section>

    <section class="section-calendar">
      <div class="section-calendar__left">
        
          <div class="section-calendar__container">
            <button class="section-calendar__button button-schedule">
              <svg xmlns="http://www.w3.org/2000/svg"
                class="section-calendar__image button-schedule icon icon-tabler icon-tabler-clock-hour-4" width="44"
                height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#2c3e50" fill="none" stroke-linecap="round"
                stroke-linejoin="round">
                <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                <path d="M12 12m-9 0a9 9 0 1 0 18 0a9 9 0 1 0 -18 0" />
                <path d="M12 12l3 2" />
                <path d="M12 7v5" />
              </svg>
              <p class="section-calendar__p">Schedule</p>
            </button>
            <button class="section-calendar__button">
              <svg xmlns="http://www.w3.org/2000/svg" class="section-calendar__image icon icon-tabler icon-tabler-list"
                width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#000000" fill="none"
                stroke-linecap="round" stroke-linejoin="round">
                <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                <path d="M9 6l11 0" />
                <path d="M9 12l11 0" />
                <path d="M9 18l11 0" />
                <path d="M5 6l0 .01" />
                <path d="M5 12l0 .01" />
                <path d="M5 18l0 .01" />
              </svg>
              <p class="section-calendar__p">Tracking</p>
            </button>
            <button class="section-calendar__button">
              <svg xmlns="http://www.w3.org/2000/svg"
                class="section-calendar__image icon icon-tabler icon-tabler-calendar-event" width="44" height="44"
                viewBox="0 0 24 24" stroke-width="1.5" stroke="#2c3e50" fill="none" stroke-linecap="round"
                stroke-linejoin="round">
                <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                <path d="M4 5m0 2a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-12a2 2 0 0 1 -2 -2z" />
                <path d="M16 3l0 4" />
                <path d="M8 3l0 4" />
                <path d="M4 11l16 0" />
                <path d="M8 15h2v2h-2z" />
              </svg>
              <p class="section-calendar__p">Organize</p>
            </button>
          </div>

          <div>
            <p>
              <strong>Schedule tasks to keep</strong> to keep track of their
              completion. Sync provides multiple scheduling options including
              alarms and reminders
            </p>

            <div>

              <div class="section-calendar__checklist">
                <img class="check-icon" src="images/checkIcon.png" alt="icono check" />
                <p>
                  You can always add new tasks or change the settings of existing
                  ones in your calendar view or the app control panel
                </p>
              </div>

              <div class="section-calendar__checklist">
                <img class="check-icon" src="images/checkIcon.png" alt="icono check" />
                <p>
                  It's easy to stay focused on your most important daily activities
                  that get you closer to meeting your goals
                </p>
              </div>
              <div class="section-calendar__checklist">
                <img class="check-icon" src="images/checkIcon.png" alt="icono check" />
                <p>
                  Use phone reminders to free up your long term memory wich will
                  reduce stress and make you more productive
                </p>
              </div>
            </div>

            <div class="container-buttons__privacy">
              <button class="button-terms">TERMS</button>
              <button class="button-privacy">PRIVACY</button>
            </div>
          </div>
        </div>
        
          <img id="calendar-image" src="images/description-2-app.png" alt="imagen fondo 2" />
        

    </section>

    <section class="section-user">
      <h2>User Testimonials</h2>

      <!--Iconos Estrellas-->

      <div class="section-user__rick">
        <img class="section-user__rick__img" src="images/iconoEstrellasFix.png" alt="icono valoraciones" />
        <p class="section-user__rick__p">
          I love using Sync for my personal development needs. It meets all my
          requirements and it actually helps a lot with focusing skills.
        </p>
        <p class="section-user__rick__p"><strong>Rick Jones - Designer</strong></p>
      </div>

      <div class="section-user__lynda">
        <img class="section-user__lynda__img class=" src="images/iconoEstrellasFix.png" alt="icono valoraciones" />
        <p class="section-user__lynda__p">
          After trying out a large number of personal coaching apps I decided
          to give Sync a try and what a wonderful surprise it was.
        </p>
        <p class="section-user__lynda__p"><strong>Lynda Marquez - Developer</strong></p>
      </div>

      <div class="section-user__jay">
        <img class="section-user__jay__img" src="images/iconoEstrellasFix.png" alt="icono valoraciones" />
        <p class="section-user__jay__p">
          Never dreamed I could learn so fast how to focus on my personal
          goals and improve my life to levels I never thought possible.
        </p>
        <p class="section-user__jay__p"><strong>Jay Frisco - Marketer</strong></p>
      </div>

      <div class="section-user__customers">
        <img class="section-user__customers__img" src="images/customer-logo-1.png" alt="customer logo 1" />
        <img class="section-user__customers__img" src="images/customer-logo-2.png" alt="customer logo 2" />
        <img class="section-user__customers__img" src="images/customer-logo-3.png" alt="customer logo 3" />
        <img class="section-user__customers__img" src="images/customer-logo-4.png" alt="customer logo 4" />
        <img class="section-user__customers__img" src="images/customer-logo-5.png" alt="customer logo 5" />
      </div>

      <div class="section-user__frank">
        <img class="section-user__frank__img" src="images/iconoEstrellasFix.png" alt="icono valoraciones" />
        <p class="section-user__frank__p">
          I got so much value from using Sync in my daily life for wich I am
          very grateful and would recommend it to everybody
        </p>
        <p class="section-user__frank__p"><strong>Frank Gibson - Manager</strong></p>
      </div>

      <div class="section-user__rita">
        <img class="section-user__rita__img" src="images/iconoEstrellasFix.png" alt="icono valoraciones" />
        <p class="section-user__rita__p">
          If you have great goals but can't figure out a way to keep focused
          then you should definitely give Sync a try and see the results
        </p>
        <p class="section-user__rita__p"><strong>Rita Longmile - Designer</strong></p>
      </div>

      <div class="section-user__jones">
        <img class="section-user__jones__img" src="images/iconoEstrellasFix.png" alt="icono valoraciones" />
        <p class="section-user__jones__p">
          I've been looking for a great organizer app for such a long time but
          now I am really happy that I found Sync. It's been working great
        </p>
        <p class="section-user__jones__p"><strong>Jones Smith - Developer</strong></p>
      </div>
    </section>

    <section class="section-numbers">
      <div class="section-numbers__container section-numbers__users">
        <img src="images/usersIconFix.png" alt="users icon" />
        <p class="section-numbers__container__number">231</p>
        <p>Happy Users</p>
      </div>

      <div class="section-numbers__container section-numbers__keys">
        <img src="images/keyIconFix.png" alt="keys icon" />
        <p class="section-numbers__container__number">385</p>
        <p>Issues Solved</p>
      </div>

      <div class="section-numbers__container section-numbers__gear">
        <img src="images/gearIconFix.png" alt="gear icon" />
        <p class="section-numbers__container__number">159</p>
        <p>Good Reviews</p>
      </div>

      <div class="section-numbers__container section-numbers__messages">
        <img src="images/messageIconFix.png" alt="messages icon" />
        <p class="section-numbers__container__number">127</p>
        <p>Case Studies</p>
      </div>

      <div class="section-numbers__container section-numbers__rocket">
        <img src="images/rocketIconFix.png" alt="rocket icon" />
        <p class="section-numbers__container__number">211</p>
        <p>Orders Received</p>
      </div>
    </section>

    <section class="section-bottom">
      <div class="section-bottom__image">
        <img id="phone-image-bottom" src="images/download-iphone.png" alt="imagen fondo 4" />
      </div>
      
      <div class="section-bottom__container">
      <p class="section-bottom__container__p">
        Do you feel like you're wasting time with small stuff instead of
        working towards your goals? Start using Sync to organize your time and
        get a grip on your personal development
      </p>

      <div class="button-download">
        <button class="button-download__button">
          <svg class="button-download__icon" xmlns="http://www.w3.org/2000/svg"
           width="44" height="44" viewBox="0 0 24 24"
            stroke-width="1.5" stroke="none" fill="#ffff" stroke-linecap="round" stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
            <path
              d="M9 7c-3 0 -4 3 -4 5.5c0 3 2 7.5 4 7.5c1.088 -.046 1.679 -.5 3 -.5c1.312 0 1.5 .5 3 .5s4 -3 4 -5c-.028 -.01 -2.472 -.403 -2.5 -3c-.019 -2.17 2.416 -2.954 2.5 -3c-1.023 -1.492 -2.951 -1.963 -3.5 -2c-1.433 -.111 -2.83 1 -3.5 1c-.68 0 -1.9 -1 -3 -1z" />
            <path d="M12 4a2 2 0 0 0 2 -2a2 2 0 0 0 -2 2" />
          </svg>
          <p>Download</p>
        </button>
        <button class="button-download__button">
          <svg class="button-download__icon" xmlns="http://www.w3.org/2000/svg"
           width="44" height="44" viewBox="0 0 24 24"
            stroke-width="1.5" stroke="#ff556e" fill="#fff" stroke-linecap="round" stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
            <path
              d="M4 3.71v16.58a.7 .7 0 0 0 1.05 .606l14.622 -8.42a.55 .55 0 0 0 0 -.953l-14.622 -8.419a.7 .7 0 0 0 -1.05 .607z" />
            <path d="M15 9l-10.5 11.5" />
            <path d="M4.5 3.5l10.5 11.5" />
          </svg>
          <p>Download</p>
        </button>
      </div>
    </div>
    </section>
  </main>

  
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

/* Main */
/* .mobile-landing {
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

.button-download__icon {
    width: 22px;
    height: 22px;
}


.button-download button {
    display: flex;
    margin: 5px;
    padding: 5px 20px;
    color: #ffff;
    text-transform: uppercase;
    border: 2px solid #ff556e;
    font-size: 14px;
    font-weight: 700;
    border-radius: 28px;
    background-color: #ff556e;
}

.button-download button:hover {
    background-color: #fff;
    border: 2px solid #ff556e;
    color: #ff556e;
}

Correccion icono apple boton download
.button-download:hover .button-download__icon {
    stroke: #ff556e;
}

.button-download {
    display: flex;
    justify-content: center;
    margin-top: 50px;
}

.button-download__button p {
    margin: auto;
    margin-left: 5px;
}

.container-image-phone {
    display: flex;
    justify-content: center;
}

.phone-image {
    width: 929px;
    margin-top: 50px;
}

/* .phone-image:hover {
    transform: scale(1.2);
    transition: all 0.2s;
} */ 

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

.icons-middle__text {
    font-weight: 700;
    text-align: center;
    margin-top: 50px;
}

/* Seccion organize */

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

.lightbox-button {
    background-color: #ff556e;
    border-radius: 28px;
    border: 2px solid #ff556e;
    width: 150px;
    height: 40px;
    font-weight: 700;
    color: #fff;
}

.lightbox-button:hover {
    background-color: #fff;
    color: #ff556e;
    border: 2px solid #ff556e;
    transition: all 0.2s;
}

/* section calendar */
.section-calendar {
    display: flex;
    justify-content: center;
    background-color: #e8eff6;
    padding: 128px 0;
}

.section-calendar__left {
    display: flex;
    flex-direction: column;
    width: 570px;
    height: 586px;
    font-size: 16px;
    padding: 96px 40px 0 0 ;
    opacity: 0.6;
}

.section-calendar__container {
    display: flex;
    gap: 10px;
    padding: 10px;
}

.section-calendar__button {
    display: flex;
    width: 150px;
    height: 40px;
    border: none;
    background-color: #fff;
    justify-content: center;
    align-items: center;
    padding: 0 5px;  
}

.section-calendar__button:hover {
    background-color: #9a67e7;
    color: #fff;
}

.section-calendar__button:hover svg {
    stroke: #fff;
}

.section-calendar__image {
    width: 22px;
    height: 22px;
}

.section-calendar__p {
    padding: 0 5px;
    font-weight: 700;
}

.button-schedule {
    background-color: #9a67e7;
    color: #fff;
}

.button-schedule svg {
    stroke: #fff;
}

#calendar-image {
    width: 497px;
    height: 586px;
    position: relative;
}

.check-icon {
    width: 22px;
    height: 22px;
}

.section-calendar__checklist{
    display: flex;
    align-items: center;
    margin-left: 10px;
}

.section-calendar__checklist p {
    margin-left: 10px;
}

.button-terms {
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


</style>
