<template>
  <header>
    <div>
      <a href="#"><img id="top-icon" src="images/logo.svg" alt="top left icon" /></a>
    </div>
    <div>
      <nav>
        <ul class="top-menu">
          <li><a href="#">Description</a></li>
          <li><a href="#">Features</a></li>
          <li><a href="#">Screens</a></li>
          <li class="dropdown">
            <a href="#">Extra</a>
            <div class="dropdown-content">
              <a href="#">Article Details</a>
              <a href="#">Terms Conditions</a>
              <a href="#">Privacy Policy</a>
            </div>
          </li>
          <li>
            <a href="https://factoriaf5.org/"><button class="button-download__top">Download</button></a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style scoped>
#top-icon {
    width: 6.688rem;
    margin-left: 100px; 
}
nav {
    width: 70%;
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

/*   desde aqui             */
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
/*     hasta aqui        */

.top-menu a:hover{
    color: #ff556e;
}
</style>