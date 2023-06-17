<script lang="ts">
  export let image: string;
  export let alt: string;
  export let link: string = "#";
</script>

<a href={link}>
  <img {alt} src={image} />
</a>

<style>
  img {
    width: 2rem;
    padding: 0.1rem;
  }
</style>
