<script setup></script>

<template>
  <nav>
    <div class="top-nav-left">
      <img
        src="https://omuscmslfrpcdn03.azureedge.net/o/Otis-New-theme/images/assets/otis-logo.png"
      />
    </div>
    <div class="top-nav-right">
      <div>
        <div>Otisline (800) 233-6847</div>
        <div>Customer Login</div>
        <div>Newsroom</div>
        <div>Blog</div>
        <div>Careers</div>
        <img src="./assets/united-states.png" height="30px" />
      </div>
      <div style="color: white; gap: 30px">
        <div>Products & Services</div>
        <div>Tools & Resources</div>
        <div>Our Company</div>
        <div>Investors</div>
        <div>Contact Us</div>
        <i class="fa fa-search" style="font-size: 20px; color: white"></i>
      </div>
    </div>
  </nav>
  <main>
    <div class="main-inner-center">
      <h2>This website is an example of my work.</h2>
      <p>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Placeat at
        consequuntur qui in. Eius officia optio id illum atque quisquam
        perferendis debitis possimus corporis consequatur, sint dicta laborum
        deleniti dolores!
      </p>
      <button>Join Our Talent Community</button>
    </div>
  </main>
  <div class="bottom-main-wrapper">
    <div class="bottom-main">
      <img
        src="https://www.otis.com/documents/256045/366802531/mtmc-map.png/ab75d0ba-8547-dae7-91ab-7d6d0baa2e8e?t=1649168519977"
        width="100%"
        height="280px"
      />
      <p class="p-1">
        We are the world's leading company for elevator and escalator
        manufacturing.
      </p>
      <p>
        We move 2 billion people a day and maintain more than 2 million customer
        units worldwide - the world's largest portfolio. We can be found in many
        of the world's most recognizable buildings as well as the busiest
        transportation hubs and retail centers. We are everywhere people are on
        the move.
      </p>
      <button>Our Company</button>
    </div>
  </div>
</template>

<style scoped>
nav {
  display: flex;
  justify-content: space-between;
  background-color: rgb(9, 28, 56);
  color: rgb(196, 149, 81);
  padding: 20px 40px;
  align-items: center;
}

.top-nav-right > div {
  display: flex;
  gap: 30px;
  align-items: center;
}

.top-nav-right {
  display: none;
}

.top-nav-right > div {
  text-transform: uppercase;
}

.top-nav-right {
  display: none;
}

main {
  height: 500px;
  background-size: cover;
  background-position: center;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: rgba(0, 0, 0, 0.65)
    url(https://omuscmslfrpcdn03.azureedge.net/documents/d/otis-2/lv_otis_bondst_dsc_0182-hero);
  background-blend-mode: darken;
}

.main-inner-center {
  max-width: 800px;
  padding: 20px 40px;
  color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 10px;
}

.main-inner-center button {
  width: fit-content;
  background-color: transparent;
  padding: 10px 40px;
  border: 2px solid white;
  color: white;
  text-transform: uppercase;
  cursor: pointer;
}

.main-inner-center button:hover {
  background-color: white;
  color: black;
}

@media only screen and (min-width: 1100px) {
  .top-nav-right {
    display: flex;
    flex-direction: column;
    gap: 20px;
    align-items: flex-end;
  }
}

h2 {
  font-size: 2rem;
}

.bottom-main-wrapper {
  background-color: rgb(233, 231, 229);
  display: flex;
  justify-content: center;
}

.bottom-main {
  display: flex;
  flex-direction: column;
  gap: 20px;
  padding: 20px 40px;
  max-width: 700px;
}

.bottom-main button {
  background-color: rgb(9, 28, 56);
  color: white;
  padding: 10px 40px;
  border: none;
  width: fit-content;
  cursor: pointer;
}

.bottom-main button:hover {
  background-color: transparent;
  color: rgb(9, 28, 56);
  outline: 2px solid rgb(9, 28, 56);
}

.p-1 {
  font-size: 1.6rem;
}
</style>
