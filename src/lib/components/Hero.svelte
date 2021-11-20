<script>
  import SocialButtons from "./SocialButtons.svelte";
</script>
<div class="hero bg-base-200">
	<div class="flex-col hero-content md:flex-row-reverse py-10 px-6">
		<img src="/me.jpg" class="max-w-xs rounded-lg shadow-2xl"/>
		<div class="mr-5">
			<h2 class="mb-5 text-4xl font-bold">Michael O'Connell</h2>
			<p class="mb-5">
        👋 Hey, I'm Michael O'Connell. I play in two bands, Factotem and Keep Sketch, in which I am both a drummer and a songwriter.
        I write a tonne of music, some of which I decide to sing, and record by myself. This is a place for that music.
      </p>
			<SocialButtons />
			<div class="flex flex-row mt-5 flex-wrap">
				<a target="_blank" href="https://open.spotify.com/artist/1U2kwOerqO1ARTFYCZXhJB" class="btn">Listen on Spotify</a>
				<a target="_blank" href="https://michaeloc.bandcamp.com/" class="btn">Listen on BandCamp</a>
				<a target="_blank" href="https://soundcloud.com/michaeloconnellmusic" class="btn">Listen on SoundCloud</a>
			</div>
		</div>
	</div>
</div>
<div class="aspect-w-16 aspect-h-9">
  <iframe src="https://www.youtube.com/embed/4yERp9_Tdt4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>