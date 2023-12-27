<script>
  let count = 0;

  function increment() {
    count += 1;
  }

  function decrement() {
    count -= 1;
  }
</script>

<main>
  <h1>Counter App</h1>
  <p>Count: {count}</p>
  <button on:click={increment}>Increment</button>
  <button on:click={decrement}>Decrement</button>
</main>

<style>
  main {
    text-align: center;
    margin-top: 2em;
  }

  button {
    font-size: 1em;
    margin: 0 0.5em;
    padding: 0.5em 1em;
    cursor: pointer;
  }
</style>
