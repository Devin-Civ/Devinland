<h1 class="title">Devin Civiello</h1>

<p class="description">
	Thanks for visiting my website! This will be a place to share things that I like. I'm doing all
	the styling by hand (no AI) to both improve my CSS skills and so that hopefully the end product is
	a more unique expression of my personality.
</p>

<div class="media-section">
	<div class="media-container">
		<div class="video-frame">
			<iframe
				title="UConn stuns Duke on Braylon Mullins' miracle last-second triple — ESPN"
				src="https://www.espn.com/watch/syndicatedplayer/_/id/48342989"
				allowfullscreen
			></iframe>
		</div>
		<div class="video-caption">
			<p>In case you missed it</p>
		</div>
	</div>
</div>

<style>
	.title {
		text-align: center;
	}
	.description {
		font-size: 1.2rem;
		color: #000;
		margin: 2rem;
	}
	.media-section {
		display: flex;
		justify-content: center;
	}
	.media-container {
		width: 100%;
		max-width: 48rem;
		margin: 2rem;
	}
	.video-frame {
		width: 100%;
		aspect-ratio: 16/9;
		border-radius: 8px;
		overflow: hidden;
	}
	.video-frame iframe {
		width: 100%;
		height: 100%;
		border: 0;
	}
	.video-caption {
		font-size: 0.8rem;
		color: #000;
		font-style: italic;
	}
</style>
