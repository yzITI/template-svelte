<svelte:head>
  <title>ITI</title>
</svelte:head>

<script>
let cot = 0
</script>

<div class="p-2">
  <div>Hello, world!</div>
  <div>cot = { cot }</div>
  <button on:click={ () => cot++ }>Click me!</button>
</div>