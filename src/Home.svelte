<script>
  let a = 0;
  let b = 0;
  let c = 0;

  const generate = () => {
    let m = Math.floor(Math.random() * 100);
    let n = Math.floor(Math.random() * 100);
    a = Math.abs(2 * m * n);
    b = Math.abs(m * m - n * n);
    c = Math.abs(m * m + n * n);
  };
</script>

<div class="bg">
  <h1>Welcome to <br /> Pythagorean Triple <br /> Generator</h1>
  <p>a = {a} | b = {b} | c = {c}</p>
  <button class="waves-effect waves-light btn" on:click={generate}
    >Generate Triple</button
  >
</div>

<style>
  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  .btn {
    border-radius: 0.625rem;
  }
  .bg {
    position: relative;
    top: 1.5rem;
  }
</style>
