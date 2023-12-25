<script>
	let name = 'world';
</script>

<header>
	<div class="corner" id="left"><img src="https://i.imgur.com/WW83jII.gif"/> </div>

	<div class="corner" id="right"><img src="https://i.imgur.com/cPKMT4b.gif" /></div>
	
</header>
<div class="quote">
	<p style="text-indent: 25px;">There is enough shit in life to deal with.</p>
		<p style="text-indent: 50px;">These phone sounds are definitely not shit.</p>
	<p id="enjoy">Enjoy.</p>
	
 </div>

<main>

	
	
</main>

<style>
	header {
		display: flex;
		background: linear-gradient(to right, #656565,#040404 )

	
	}

		#right {
			position:absolute;
			right:5%;
		}
	.corner {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 15em;
		height: 15em;
		margin-left: 0.5em;
	}

	.corner img {
		
		height: 15em;
		object-fit: contain;
		margin-left:5em;
	}
p{
	margin:0;
}

#enjoy{
	float:right;
	font-size: 2em;
	color: rgb(72, 113, 201);
}
	.quote {
		display:flex;
		flex-direction: column;
		align-items: flex-end;
		font-family: "Style Script", cursive;
		border: 3px groove;
		font-size: 2.5em;
		max-width: max-content;
		max-height: max-content;
		margin-top:50px;
		
}
</style>