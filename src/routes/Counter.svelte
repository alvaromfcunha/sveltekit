<script>
  let counter = 0

  function addCounter() {
    counter += 1
  }
  function subCounter() {
    counter -= 1
  }
</script>

<button on:click={addCounter}>+</button>
{counter}
<button on:click={subCounter}>-</button>