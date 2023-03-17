<script>
  let count = 0
  const increment = () => {
    count += 1
  }
</script>

<button class="btn glass w-60 " on:click={increment}>
  count is {count}
</button>
