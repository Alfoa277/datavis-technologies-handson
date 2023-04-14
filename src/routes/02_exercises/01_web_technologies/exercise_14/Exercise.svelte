<script>
  let current = "";

</script>

<style>
  .btn_primary {
    background-color: rosybrown;
  }
</style>

<!-- We will cover buttons later on! -->
<button class="btn btn-secondary" class:btn_primary={current == "messi"} on:click={() => (current = "messi")}>
  Messi
</button>

<button class="btn btn-secondary" class:btn_primary={current == "ronaldo"} on:click={() => (current = "ronaldo")}>
  Ronaldo
</button>

<button class="btn btn-secondary" class:btn_primary={current == "neymar"} on:click={() => (current = "neymar")}>
  Neymar
</button>


