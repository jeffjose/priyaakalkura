<style>
  .wrapper {
    height: 100%;
    display: grid;
    grid-template-columns: 1fr [content-start] 4fr [content-end] 1fr;
    grid-template-rows: 1fr [content-start] 4fr [content-end] 1fr;
  }

  .contents {
    grid-column: content;
    grid-row: content;
    align-items: center;
    justify-items: center;
  }

  h1 {
    text-align: center;
  }
</style>

<svelte:head>
	<title>Priyaa Kalkura</title>
</svelte:head>

<div class="wrapper">
  <div class="contents">
    <h1>Hi!</h1>
    <h3>I'm Priyaa Kalkura, and I'm a hollywood production executive currently at DreamWorks Animation.</h3>
  </div>
</div>
