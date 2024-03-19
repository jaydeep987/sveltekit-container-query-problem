<div class="main">
  <h1>Welcome to SvelteKit</h1>
  <p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
</div>


<style lang="css">
  .main {
    container-name: myContainer;
    container-type: inline-size;
  }
  @container myContainer (min-width: 300px) {
      h1 {
        color:red;
      }
    }
</style>