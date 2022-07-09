<script>
  let count = 0
  const increment = () => {
    count += 1
  }
</script>


<button on:click={increment} class="button is-rounded is-size-1 is-bold is-primary">
  Clicks: {count}
</button>

<style>


  button:focus {
    border: 2px solid #ff3e00;
  }

  button:active {
    background-color: rgba(255, 62, 0, 0.2);
  }
</style>
