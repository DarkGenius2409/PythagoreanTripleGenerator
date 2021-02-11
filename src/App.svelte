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
  .container {
    width: auto;
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
  /* Extra small devices (phones, 600px and down) */
  @media only screen and (max-width: 600px) {
    .container {
      width: 85vw;
    }
  }
</style>
