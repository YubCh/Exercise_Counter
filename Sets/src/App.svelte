<script>
	let count = 1;
</script>

<main>
	<h3>Counts Left</h3>
	<p>{count}</p>
	<button class="b b1" on:click={()=> count++}> + </button>
	<button class="b b2" on:click={()=> count--}> - </button>
	<button class="b b3" on:click={()=> count += 10}> +10 </button>
	<button class="reset" on:click={()=> count = 0}> Reset </button>
</main>


<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
		font-size: 50px;
	}

	h3{
		font-size: 50px;
	}

	.b{
		text-align: center;
		max-width: 240px;
		max-height: 240px;
		font-size: 50px;
	}
	
	.b1{
		background-color: aqua;
	}
	.b1:hover{
		background-color: aquamarine;
	}
	.b2{
		background-color: lightcoral;
	}
	.b2:hover{
		background-color: pink;
	}
</style>