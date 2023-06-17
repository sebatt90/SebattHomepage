<script lang="ts">
  import github_logo from "../assets/github-mark.svg";

  export let card_title: string = "GitHub Project";
  export let card_desc: string = "Description";
  export let text: string = "Lorem Ipsum";
  export let github_link: string = "#";
</script>

<div id="card" class="col">
  <div class="card" style="width: 18rem;">
    <div class="card-body">
      <h5 class="card-title">{card_title}</h5>
      <h6 class="card-subtitle mb-2 text-body-secondary">{card_desc}</h6>
      <p class="card-text">
        {text}
      </p>
      <a href={github_link} class="card-link">
        <img alt="Github" src={github_logo} />
      </a>
    </div>
  </div>
</div>

<style>
  #card {
    padding: 1rem;
  }

  img {
    width: 2rem;
    height: 2rem;
  }
</style>
