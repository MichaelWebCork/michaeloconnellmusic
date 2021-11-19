<script>
  import ArtistBio from "$lib/components/a-week-alone/ArtistBio.svelte";
  import Artwork from "$lib/components/a-week-alone/Artwork.svelte";
  import Hero from "$lib/components/a-week-alone/Hero.svelte";
  import Playlist from "$lib/components/a-week-alone/Playlist.svelte";
  import SocialButtons from "$lib/components/SocialButtons.svelte";
</script>

<Hero/>
<Playlist/>
<ArtistBio/>
<Artwork/>
<div class="p-6 bg-base-200 rounded-lg mb-2">
  <h2 class="mb-5 text-1md font-bold">My social media links:</h2>
  <SocialButtons/>
  <ol class="mt-5 ml-10 mb-5 list-decimal">
    <li>Facebook - <a class="link" target="_blank" href="https://facebook.com/michaeloconnellmusic/">https://facebook.com/michaeloconnellmusic/</a></li>
    <li>Instagram - <a class="link" target="_blank" href="https://www.instagram.com/michaeloconnellmusic/">https://www.instagram.com/michaeloconnellmusic/</a></li>
    <li>YouTube - <a class="link" target="_blank" href="https://www.youtube.com/channel/UCFR0JYHigNA57sqzJL_SBTg">https://www.youtube.com/channel/UCFR0JYHigNA57sqzJL_SBTg</a></li>
    <li>Twitter - <a class="link" target="_blank" href="https://twitter.com/michaelocmusic">https://twitter.com/michaelocmusic</a></li>
    <li>Spotify - <a class="link" target="_blank" href="https://open.spotify.com/artist/1U2kwOerqO1ARTFYCZXhJB">https://open.spotify.com/artist/1U2kwOerqO1ARTFYCZXhJB</a></li>
    <li>BandCamp - <a class="link" target="_blank" href="https://michaeloc.bandcamp.com/">https://michaeloc.bandcamp.com/</a></li>
    <li>SoundCloud - <a class="link" target="_blank" href="https://soundcloud.com/michaeloconnellmusic">https://soundcloud.com/michaeloconnellmusic/</a></li>
  </ol>
</div>
<div class="aspect-w-16 aspect-h-9">
  <iframe src="https://www.youtube.com/embed/fWRr7Vm2G0A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>