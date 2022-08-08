<script>
	import { ArrowSide, Glass, Tab, Svg } from "./components/components.js"
</script>

<Tab/>

		<div class="glass">
			<Glass/>
		</div>

		<div class="arrow">
			<ArrowSide/>
		</div>

		<div class="svg">
			<Svg/>
		</div>

		<div class="path">
			<img src="path.svg" alt="programming path"/>
		</div>
	

<style>

	.svg {
		display: none;
	}

	.arrow {
		position:relative;
		top: -180px;
		left: 40%;
	}


	.path {
		position: relative;
		top: -400px;
		left: 50%;
		height: 500px;
		width: 670px ;
		background: rgba(224,241,247,0.71);
		border-radius: 20px;
		border: 2px solid #fff;
		overflow: hidden;
	}

	@media screen and (max-width: 790px) {

	.svg {
		display: inline;
		left: 66px;
	}
		.path{
			position: relative;
			top: 300px;
			left:20px;
			height:419px;
			width: 420px;
		}

		.svg {
			position:relative;
			top: 270px;
		}

		.arrow {
			display: none;
		}
         }
</style>
