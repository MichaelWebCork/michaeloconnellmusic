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
        I write a tonne of music, some of which I decide to sing, and record by myself.
      </p>
			<p class="mb-8">
        This is my genral EPK, there are also release specific EPKs. Currently, I am gearing up to release "a week alone", my newest 2 track ep.
      </p>
			<a href="/a-week-alone-epk" class="btn btn-outline mb-5">Go to latest release EPK</a><br>
      <SocialButtons />
		</div>
	</div>
</div>
