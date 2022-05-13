<script>
import GlassmorphismCard from "$lib/GlassmorphismCard.svelte";

</script>
<header>
  <h1>emz<span>.dev</span></h1>
  <GlassmorphismCard text={"Hola! Soy Ernesto Martínez, subo artículos sobre desarrollo web"} width={"70%"}/>
</header>

<style>
  header {
    background-image: url("rocket.jpg");
    background-size: cover;
    background-position: 45%;
    width: 95%;
    min-height: 400px;
    height: 100vh;
    max-height: 90vh;
    border-radius: .7rem;
    font-family: 'Roboto', sans-serif;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  h1 {
    font-family: 'Montserrat', sans-serif;
    font-size: 7rem;
    font-weight: bold;
  }


  span {
    color: #f3f3f3;
    text-shadow:
    -2px -2px 0 #000000,
    2px -2px 0 #000000,
    -2px 2px 0 #000000,
    2px 2px 0 #000000,  
    -3px 0 0 #000000,
    3px 0 0 #000000,
    0 3px 0 #000000,
    0 -3px 0 #000000;
  }

</style>