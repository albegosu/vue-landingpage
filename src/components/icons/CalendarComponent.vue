<template>
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
                <ul>
                    <li class="checkmark"> You can always add new tasks or change the settings of existing
                  ones in your calendar view or the app control panel</li>
                    <li class="checkmark">It's easy to stay focused on your most important daily activities
                  that get you closer to meeting your goals</li>
                    <li class="checkmark">Use phone reminders to free up your long term memory wich will
                  reduce stress and make you more productive</li>

                </ul>
            </div>

            <div class="container-buttons__privacy">
              <button class="button-terms">TERMS</button>
              <button class="button-privacy">PRIVACY</button>
            </div>
          </div>
        </div>
        
        <img id="calendar-image" src="/src/assets/description-2-app.png" alt="imagen fondo 2" />
    </section>
</template>

<style scoped>
/* section calendar */
.section-calendar {
    display: flex;
    flex-direction: column;
    justify-content: center;
    background-color: #e8eff6;
    padding: 128px 0;
}

#calendar-image {
    order: 1;
}

@media (min-width: 800px) {
    .section-calendar {
        display: flex;
        flex-direction: row;
        justify-content: center;
        background-color: #e8eff6;
        padding: 128px 0;
    }
    #calendar-image {
    order: 2;
    }    
}

.section-calendar__left {
    display: flex;
    flex-direction: column;
    width: 570px;
    height: 586px;
    font-size: 16px;
    padding: 96px 40px 0 0 ;
    opacity: 0.6;
    order: 2;
}

.checkmark {
    list-style-image: url(src/assets/checkmark.png);
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
</style>