<script>
  import Home from "./Home.svelte";
  import WhatIsThis from "./WhatIsThis.svelte";
  import HowThisWorks from "./HowThisWorks.svelte";
  import Footer from "./Footer.svelte";
</script>

<nav>
  <div class="nav-wrapper">
    <div class="container">
      <a class="brand-logo left" href="#home">Pythagorean Triple Generator</a>
      <ul class="right">
        <li><a href="#what-is-this">What is this</a></li>
        <li><a href="#how-this-works">How does this work</a></li>
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
</style>
