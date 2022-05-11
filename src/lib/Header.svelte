<script>
import GlassmorphismCard from "./GlassmorphismCard.svelte";

</script>
<header>
  <h1>emz<span>.dev</span></h1>
  <GlassmorphismCard text={"Hola! Soy Ernesto Martínez, subo artículos sobre desarrollo web"} width={"70%"}/>
</header>

<style>
  header {
    background-image: url("../assets/rocket.jpg");
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

  p {
    font-size: 2rem;
    text-align: center;
    color: #f3f3f3;
  }

  .text-container {
    width: 70%;
    background: rgba( 0, 0, 0, 0.25 );
    box-shadow: 0 8px 32px 0 rgba( 31, 38, 135, 0.37 );
    backdrop-filter: blur( 4px );
    -webkit-backdrop-filter: blur( 4px );
    border-radius: 10px;
    border: 1px solid rgba( 255, 255, 255, 0.18 );
    padding: 1rem;
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