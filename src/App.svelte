<script>
	let name = 'world';

	let count = 0;
	function incrementCount() {
		count += 1;
	}

	let llama_image = "../images/baby_llama.png";

</script>


<header> 
	<title>Practice site</title>

</header>
<body>

<div class="container">
	<h1>Hello {name}!</h1>

	<button on:click={incrementCount}>
		Clicked {count} {count === 1 ? 'time' : 'times'}
	
	</button>
	
	<hr> 
	
	<p1>Hello hello!</p1>

	<hr>

	<img src={llama_image} alt="minecraft baby llama">
	
</div>

</body>
