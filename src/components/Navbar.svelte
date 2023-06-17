<script lang="ts">
  import youtube from "../assets/youtube.svg";
  import github from "../assets/github-mark-white.svg";
  import Link from "./Link.svelte";
</script>

<div>
  <nav class="navbar bg-dark border-bottom border-bottom-dark">
    <div class="container-fluid">
      <a href="#" class="navbar-brand text-white">sebatt90</a>

      <div>
        <Link
          image={youtube}
          alt={"YouTube"}
          link="https://www.youtube.com/channel/UCrQoo8R0JcJFcAXcEcCWVTg"
        />
        <Link
          image={github}
          alt={"GitHub"}
          link="https://github.com/sebatt90/"
        />
      </div>
    </div>
  </nav>
</div>
