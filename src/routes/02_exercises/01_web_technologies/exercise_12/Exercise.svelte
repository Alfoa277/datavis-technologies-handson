<script>
	let clicked = false;
</script>

<div>
	<button class="btn btn-primary" on:click={() => (clicked = true)}>
		click here
	</button>
</div>

{#if clicked}
You have cliked the button! yay
{:else}
... You have to click the button!
{/if}