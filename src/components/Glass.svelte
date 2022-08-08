<script>
	import Icon from 'svelte-awesome';
	import twitterSquare from 'svelte-awesome/icons/twitterSquare';
	import fileO from 'svelte-awesome/icons/fileO';
	import githubSquare from 'svelte-awesome/icons/githubSquare';
</script>


<div class="glass">
<div id="me"> 
	<strong>Brian Kipchumba Tum</strong><p>

		<strong>+254 716 012619</strong><p>
	
	
	<a href="mailto:brian.tum10@yahoo.com"><strong>brian.tum10@yahoo.com</strong><p></a>	
	<a href="https://twitter.com/BrianTum13"><Icon data={twitterSquare} scale=4 class="pinkIcon"/></a>
	<a href="https://github.com/bryo13"><Icon data={githubSquare} scale=4 /></a>
	<a href="https://drive.google.com/file/d/1uC-SoYeOTlCdIYYKiasZ-0KhlrMoA2aL/view?usp=sharing"><Icon data={fileO} label="CV" scale=4/></a>
	<img src="logo/c-logo.svg" alt="background image" />

</div>
</div>

<style>
 	@import url('https://fonts.googleapis.com/css2?family=Linden+Hill&display=swap');

	.glass {
		position: relative;
		left:50px;
		top:44px;
		width: 440px;
		height: 300px;
		background: rgba(255,255,255,0.5);
		border-radius: 20px;
		border: 2px solid #fff;
		overflow: hidden;
	}
@media screen and (max-width: 570px) {
            .glass {
		    width:350px;
		    font-size: 17px;
		    height:270px;
		    position:absolute;
		    top:90px;
		    left:18px;
            }
         }

	.glass::before {
		content:"";
		position:absolute;
		top:0;
		left:-50%;
		width: 100%;
		height:100%;
		background: rgba(255,255,255,0.5);
		pointer-events: none;
		transform: skewX(200deg);
	}

	.glass #me {
		font-family: 'Linden Hill', serif;
		font-size: 24px;
		text-align:center;
	}

</style>
