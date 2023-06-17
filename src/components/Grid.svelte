<script lang="ts">
  import Cards from "./Cards.svelte";
</script>

<div class="container">
  <div class="row">
    <Cards
      card_title={"Godot 4: Client+Server"}
      card_desc={"A Client Server socket in Godot"}
      text={"My first attempt at programming a Client-Server socket, using the Godot's API for client-side stuff and standard C#'s UDP for Server side.\
    My plan here is to create a template for any multiplayer game idea that I might have in the future. Building the server in standard C# in order to make the server more engine-agnostic."}
      github_link={"https://github.com/sebatt90/godot-client-server"}
    />
    <Cards
      card_title={"React Markdown editor"}
      card_desc={"A markdown editor designed in ReactJS"}
      text={"App made to try out React"}
      github_link={"https://github.com/sebatt90/react-markdown-editor"}
    />
    <Cards
      card_title={"Godot Train Track"}
      card_desc={"A train track with a working train made in the Godot Engine"}
      text={"A simple train track in Godot, nothing special. Made using Path and PathFollow, you can specify how many wagons your train is going to have."}
      github_link={"https://github.com/sebatt90/godot-train-track"}
    />
  </div>
</div>
