<script>
  const name = "Adithyan";
  const htmlCode = " <p>Hey here is your html</p>";
</script>

<main>
  <h1>Helloeeee {name}!</h1>
  <div>{@html htmlCode}</div>
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
