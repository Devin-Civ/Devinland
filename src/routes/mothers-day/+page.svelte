<script lang="ts">
	import flowerBorder from '$lib/assets/mothers-day/flower-border.png';
	import mom from '$lib/assets/mothers-day/me-with-mom.jpg';
</script>

<h1>Happy Mother's Day!</h1>
<div class="image-container">
	<img src={mom} alt="Me and Mom" class="main-image" />
	<img src={flowerBorder} alt="" class="flower-border" aria-hidden="true" />
</div>
<p>
	Of all the good things in this world that I've been given, you are probably my greatest blessing.<br
	/><br />
	I thank God for you all the time.<br /><br />
	I can't imagine a better mother, and somehow there's not a thing about you that I would change.<br
	/><br />
	I am so grateful for you, and I love you so very much.
</p>

<style>
	p {
		text-align: center;
		font-size: 1rem;
		font-weight: 700;
		color: #7b66a7;
		margin: 2rem;
		font-family: 'Crafty Girls', sans-serif;
	}
	h1 {
		text-align: center;
		font-family: 'Oregano', sans-serif;
		font-size: 3rem;
		color: #e6949a;
		text-shadow: 0 0 2px rgb(99, 99, 99);
	}
	.image-container {
		position: relative;
		display: block;
		width: fit-content;
		max-width: min(80vw, 56rem);
		margin-inline: auto;
		line-height: 0;
		overflow: visible;
	}

	.main-image {
		display: block;
		width: 100%;
		height: auto;
		border-radius: 1.3rem;
	}

	.flower-border {
		position: absolute;
		left: 50%;
		top: 50%;
		width: 115%;
		height: 115%;
		transform: translate(-50%, -50%);
		object-fit: fill;
		pointer-events: none;
	}
</style>
