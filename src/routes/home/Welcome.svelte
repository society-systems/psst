<script>
  import Audio from "./Audio.svelte";
</script>

<style>
  .logo {
    font-weight: normal;
    font-size: 2rem;
  }
  h1,
  p {
    color: white;
    font-size: 1.5rem;
    line-height: 1.75rem;
  }
  @media screen and (min-width: 768px) {
    p {
      width: 60%;
    }
  }
  .divider {
    font-size: 1rem;
  }
  .banner {
    flex: 1;
  }
</style>

<section class="banner">
  <h1 class="logo">psst</h1>

  <p>psst is a platform to manage popup communities</p>
</section>

<!--section class="audio">
  <Audio />
</section-->
