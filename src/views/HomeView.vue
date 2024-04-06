<template>
  <main>
    <section class="section-image">
      <div class="img-overlay"></div>
      <div class="intro">
        <div class="row">
          <div class="col-md-20">
            <h5>Hello Freinds...</h5>
            <h1>I'm Eka Rahmana Putri</h1>
            <p class="intro-desc"><span>Marksman</span>
              <span class="colour-splash">•</span>
              <span>Mage</span> <span class="colour-splash">•</span>
              <span>Support</span></p>
          </div>
          <!-- /col-md-12 -->
        </div>
        <div class="button-container">
  <div class="button">
    <a href="#about"><button>About</button></a>
    <div class="scroll"></div>
  </div>
  <div class="button">
    <a href="#skill"><button>Skill</button></a>
    <div class="scroll"></div>
  </div>
        </div>
      </div>

<!-- /intro -->
    </section>
  </main>
</template>

<style scoped>
  .section-image {
    background: #000000 url(https://c4.wallpaperflare.com/wallpaper/998/248/3/mobile-legends-angela-vespid-hd-wallpaper-thumb.jpg) no-repeat center center;
    background-size: cover;
    width: 100%;
    height: 100vh;
    position: relative;
    text-align: center;
    color: #fff;
    display: table;
  }
  button{
    border-radius: 7px;
    text-align: center;
    padding: 10px 20px;
    background-color: #bebebe;
    font-family: 'Times New Roman', Times, serif;
    font-size: 20px;
  }
.button-container {
  display: flex;
  justify-content: center; /* Center aligns the buttons horizontally */
  align-items: center; /* Aligns the buttons vertically */
}
  .img-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: #111111;
    opacity: .8; /* Adjusted overlay opacity */
  }

  .intro {
    vertical-align: middle;
    text-align: center;
    display: table-cell;
    transform: translateY(-2.1rem);
  }

  .intro .row {
    margin-right: 0;
    margin-left: 0;
  }

  .intro h1 {
    font-size: 84px;
    color: #fff; /* Changed h1 color to white */
  }

  .intro h5 {
    color: rgb(182, 187, 205);
    font-size: 2.3rem;
    margin-bottom: 3.5rem;
    text-transform: uppercase;
    letter-spacing: .5rem;
    text-shadow: 0 0 6px rgba(0, 0, 0, 0.2);
  }

  .section-image span {
    text-transform: uppercase;
    font-size: 1.4em;
    padding: 0 10px;
    font-weight: 100;
  }

  .section-image h1 {
    margin-top: 0;
  }

  .section-image p {
    font-weight: lighter;
    opacity: 0.9;
  }

  .a {
    font-family: 'Times New Roman', Times, serif;
    color: #5f1313;
  }
</style>
