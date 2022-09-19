<head>
	<style>
		:root {
 	  --background: #e9dcdc;
  	--white: #ffffff;
		}


		body{
  	  background: var(--background);
    	background-size: 400% 400%;
	    size: 10vh;
		}
		.div{
			display: flex;
  		justify-content: center;
  		align-items: center;
  		text-align: center;
  		min-height: 100vh;
		}
		button{
			background: var(--background);
			border-radius: 50px;
			border-width: 4px;
			min-width: 150px;
			min-height: 50px
		}
	</style>
	<title>Home</title>
</head>
<body class="background">
<div class="div">
<button on:click={Button}>
Show Alert
</button>
</div>
</body>


<script>
function Button(){
	alert("You Clicked!")
}
</script>