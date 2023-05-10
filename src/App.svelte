<script>
  import Counter from './lib/Counter.svelte'
  let name = "Karina";
  function showTitle() {
    const imgTitle = document.querySelector('.img-title');
    imgTitle.style.opacity = '1';
  }
</script>

<main>
  <div>
    <div class="img-container">
      <img src="./src/img/flowers.jpg" alt="Flowers" />
      <div class="img-overlay">
        <p class="img-title">Orquídea</p>
        <a href="https://es.wikihow.com/cuidar-orquídeas" target="_blank" rel="noopener noreferrer" class="img-link">Ir a otra página</a>
      </div>
    </div>
    
    
    </div>
    
    
  <h1>Vite + Svelte</h1>
  <h2>Hola como estas {name}</h2>

  <div class="card">
  </div>

  <p>
    Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank" rel="noreferrer">SvelteKit</a>, the official Svelte app framework powered by Vite!
  </p>

  <p class="read-the-docs">
    Click on the Vite and Svelte logos to learn more
  </p>
</main>

<style>
  /*.logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }*/
  .read-the-docs {
    color: #888;
  }
</style>
