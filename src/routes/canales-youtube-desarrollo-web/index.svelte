<script>
    import EntryHeader from '$lib/EntryHeader.svelte'
    import NavBar from '$lib/Navbar.svelte'
</script>

<div class="container">
    <NavBar/>
    <EntryHeader bgImg={"coffee.jpg"} title={"Canales de youtube para aprender desarrollo web"}/>
    <main>
        <p class="entry-p">
            Desde hace tiempo cada vez más personas ven en el desarrollo web una oportunidad real para trabajar, o quizás simplemente les gusta programar sus propias aplicaciones web y dejar volar su imaginación.
            En cualquier caso, aquí va una lista con canales de youtube que he encontrado muy útiles a que veo yo mismo sobre programación web.
        </p>
        <a target="_blank" href="https://www.youtube.com/c/DorianDesings">
            <h2>1. DorianDesings</h2>
            <img src="doriandesigns.png" alt="Canal de YouTube de DorianDesigns">
        </a>
        <p class="entry-p">
            Este fue el canal con el que comencé a aprender HTML, CSS y JavaScript realmente, ya que había comenzado con algunos tutoriales rápidos, pero me pareció que en este canal se explicaban mejor los conceptos y de forma "más correcta", atendiendo a buenas prácticas de desarrollo web y siempre explicando de dónde viene cada cosa que explica.
        </p>
        <p class="entry-p"><span class="best">Lo mejor:</span> Tiene muchísimo contenido gratis y muy bien ordenado. Además, se centra mucho en cosas prácticas y útiles para el desarrollo y tiene algunos videos exclusivos sobre retos de HTML o CSS donde él mismo los resuelve. Me gusta que demuestra haber trabajado muchos años en empresas como Artresmedia y la historia que tiene detrás sobre por qué comenzó a enseñar me conmovió.</p>
        <p class="entry-p"><span class="worse">Lo peor:</span> Lleva algo de tiempo sin subir video (2 meses en el momento en que escribo esto), por lo que no hay contenido nuevo. Otra cosa que a mí no me gusta es que últimamente no sube cursos gratis de ningún lenguaje o tecnología nuevos. El último es de 2021. Esto es algo personal, ya que hay mucha gente que le gusta el contenido de retos y consejos, que más bien son videos cortos y fáciles de asimilar.</p>
        <a target="_blank" href="https://www.youtube.com/c/Midudev">
            <h2>2. Midudev</h2>
            <img src="midudev.png" alt="Canal de YouTube de DorianDesigns">
        </a>
        <p class="entry-p">Es un canal genial que se centra en JavaScript y que ofrece muy buen contenido sobre frameworks como React o Svelte, siempre teniendo en cuenta buenas prácticas de desarrollo. Sube contenido muy frecuentemente y también hace directos. Tiene un canal secundario en el que sube los directos después de emitirlos.</p>
        <p class="entry-p"><span class="best">Lo mejor:</span> Hace videos muy variados y entretenidos, sobre todo enfocados en optimización del código y buenas prácticas para hacer mejores webs. Sus videos están actualizados a las últimas tecnologías y si eres un fan de JavaScript o te gustaría aprenderlo, este es tu canal.</p>
        <p class="entry-p"><span class="worse">Lo peor:</span> Lo único malo que le veo a este canal es que solo suba videos sobre desarrollo web, ya que me parece un contenido tan bueno que es una pena que se centre solo en esa temática, aunque realmente es normal que se centre en un tema para hacer mejor contenido y crear una comunidad.</p>
    </main>
</div>

<style>
    .container {
        width: 90%;
        font-family: 'Roboto', sans-serif;
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    main {
        width: 85%;
        margin-top: 4rem;
    }

    p {
        text-align: justify;
        font-size: 1.4rem;
        margin-bottom: 3rem;
        margin-top: 3rem;
    }

    h2 {
        font-size: 2.5rem;
        width: fit-content;
    }

    a {
        text-decoration: none;
        color: inherit;
        margin-left: 3rem;
    }

    a>:hover {
        text-decoration: underline;
    }

    img {
        max-width: 100%;
    }
    .best, .worse {
        font-size: 1.05em;
        font-weight: 700;
    }
    .best {
        color: #45bc71;
    }
    .worse {
        color: #ff0000;
    }

</style>