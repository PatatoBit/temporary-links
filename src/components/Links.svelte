<script>
  import LinkButton from "./LinkButton.svelte"
  import CodeIcon from "./CodeIcon.svelte"
  import YoutubeIcon from "./YoutubeIcon.svelte"
  import NoteIcon from "./NoteIcon.svelte"
  import BriefcaseIcon from "./BriefcaseIcon.svelte"
  import TwitchIcon from "./TwitchIcon.svelte"
  import HacktoberFestIcon from "./HacktoberFestIcon.svelte"
  import TwitterIcon from "./TwitterIcon.svelte"
  import InstagramIcon from "./InstagramIcon.svelte"
</script>

<div class="flex flex-col xs:flex-row flex-wrap gap-4 justify-center mt-8">
  <!-- <LinkButton href="https://garden.narze.live"><NoteIcon />Garden</LinkButton> -->
  <LinkButton href="https://github.com/narze"><CodeIcon />GitHub</LinkButton>
  <LinkButton href="https://twitter.com/PatatoBit"
    ><TwitterIcon />Twitter</LinkButton
  >
  <LinkButton href="https://www.instagram.com/art.patatotato/"
    ><InstagramIcon />Instagram</LinkButton
  >
  <!-- <LinkButton href="https://youtube.narze.live" -->
  <!-- ><YoutubeIcon />YouTube</LinkButton -->
  <!-- > -->
  <!-- <LinkButton href="https://twitch.narze.live"><TwitchIcon />Twitch</LinkButton> -->
  <!-- <LinkButton href="https://resume.narze.live"
    ><BriefcaseIcon />Résumé</LinkButton
  > -->
  <LinkButton
    href="#"
    on:click={() => {
      window.location.href = "https://youtu.be/iik25wqIuFo"
    }}>OnlyFans</LinkButton
  >
</div>
