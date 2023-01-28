<script>
	let count = 0;
</script>

<br>
<button on:click={() => count -= 1}>-</button>
<span>Svelte { count }</span>
<button on:click={() => count += 1}>+</button>