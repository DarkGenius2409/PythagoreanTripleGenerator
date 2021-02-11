<script>
  import Home from "./Home.svelte";
  import WhatIsThis from "./WhatIsThis.svelte";
  import HowThisWorks from "./HowThisWorks.svelte";
  import Footer from "./Footer.svelte";
</script>

<nav>
  <div class="nav-wrapper">
    <div class="container">
      <a class="logo" href="#home">Pythagorean Triple Generator</a>
      <ul class="right">
        <li><a class="link" href="#what-is-this">What Is This</a></li>
        <li><a class="link" href="#how-this-works">How This Works</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- <nav class="navbar navbar-expand-lg navbar-dark nav-wrapper">
  <div class="container-fluid">
    <a class="navbar-brand" href="#home">Pythagorean Triple Generator</a>
    <button
      class="navbar-toggler"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarNavAltMarkup"
      aria-controls="navbarNavAltMarkup"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon" />
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav right">
        <a class="nav-link" href="#what-is-this">What Is This</a>
        <a class="nav-link" href="#how-this-works">How THis Works</a>
      </div>
    </div>
  </div>
</nav> -->
<section id="home">
  <Home />
</section>
<section id="what-is-this">
  <WhatIsThis />
</section>
<hr />
<section id="how-this-works">
  <HowThisWorks />
</section>
<Footer />

<!-- <nav class="navbar navbar-expand-lg navbar-dark nav-wrapper">
  <div class="container-fluid">
    <a class="navbar-brand" href="#home">Pythagorean Triple Generator</a>
    <button
      class="navbar-toggler"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarNavAltMarkup"
      aria-controls="navbarNavAltMarkup"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon" />
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav right">
        <a class="nav-link" href="#what-is-this">What Is This</a>
        <a class="nav-link" href="#how-this-works">How THis Works</a>
      </div>
    </div>
  </div>
</nav> -->
<style>
  section {
    text-align: center;
    padding: 1em;
    margin: 0;
  }
  #home {
    background-color: #ffb84d;
    min-height: 75%;
  }
  hr {
    border-width: 0.3125rem;
    border-style: dotted none none;
    border-color: grey;
    width: 5%;
  }
  .nav-wrapper {
    background-color: #f48c25;
  }
  .logo {
    font-size: 1.7rem;
    margin: auto;
  }
  .link {
    font-size: 1rem;
  }
  @media only screen and (max-width: 768px) {
    .logo {
      font-size: 1.3rem;
    }
    .link {
      font-size: 0.9rem;
    }
  }
  /* Small devices (portrait tablets and large phones, 600px and up) */
  @media only screen and (max-width: 600px) {
    .logo {
      font-size: 1rem;
    }
    .link {
      font-size: 0.7rem;
    }
  }
  .right {
    text-align: end;
  }
</style>
