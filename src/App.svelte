<script>
	let name = 'world';
	let tableau = [ { id : 1, value : 10},
					{ id : 2, value : 13},
					{ id : 3, value : 20} ];
</script>

<h1>Hello {name}!</h1>

<ul>
{#each tableau as lignes }
	<li>{lignes}</li>	
{/each}
</ul>