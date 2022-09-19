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
			border-width: 5px;
			border-color: var(--background);
			border-style: solid;
			min-width: 150px;
			min-height: 50px;
			position:relative;
			box-shadow: 10px 10px 15px #888888, -10px -10px 15px #EEEEEE, inset 2px 2px 15px var(--background), inset -2px -2px 15px var(--background);
			transition:  all .2s;
			}
			button:hover{
							box-shadow: 5px 5px 15px #888888, -5px -5px 15px #EEEEEE, inset 10px 10px 15px #d9dcdc, inset -10px -10px 15px #EEEEEE;

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