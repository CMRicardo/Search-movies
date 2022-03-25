<script>
  export let initialCounter = 0;
  let counter = initialCounter;

  function handleClick() {
    counter++;
  }
</script>

<main>
  <h1>Number: {counter}</h1>
  <button on:click={handleClick}>Increment</button>
</main>

<style>
  main {
    text-align: center;
  }
  h1 {
    color: blueviolet;
  }
  button {
    border: none;
    padding: 0.5rem 1rem;
    border-radius: 5px;
    background: blueviolet;
    color: white;
  }
</style>
