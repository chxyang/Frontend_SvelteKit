<script lang="ts">
  let name = "SvelteKit";
  let img_src = "https://svelte.dev/favicon.png";
</script>

<h1>1. Hello {name} !</h1>
<p>Using Js to control the DOM is easy with {name}.</p>
<p>Welcome to the world of {name.toUpperCase()}.</p>

<h1>2. Dynamic Attributes</h1>
<!-- Using a variable for the image source, alt attribute -->
<img src={img_src} alt="Svelte logo" width="50" height="50" />
