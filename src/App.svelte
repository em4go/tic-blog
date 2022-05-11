<script>
  import Navbar from './lib/Navbar.svelte'
  import Header from './lib/Header.svelte'
import BlogEntry from './lib/BlogEntry.svelte'
</script>

<div class="main">
  <Navbar />
  <Header />
  
  <main class="articles">
    
    <div class="blog-entry-container">
      <BlogEntry 
      title={"Primer artículo del blog"}
      date={"7 de mayo de 2022"}
      imgPath={"/src/assets/coffee.jpg"}
      imgAlt={"Ilustración 3D con objetos marrones"}
      />
    </div>
  </main>
</div>

<style global>

  .main {
    width: 100vw;
    max-width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  
  main {
    width: 100%;
    margin-top: 4rem;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .blog-entry-container {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 95%;
  }
</style>
