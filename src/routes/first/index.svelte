<script>
    import EntryHeader from '$lib/EntryHeader.svelte'
    import NavBar from '$lib/Navbar.svelte'
</script>

<div class="container">
    <NavBar/>
    <EntryHeader/>
    <img src="coffee.jpg" alt="brown 3D ilustrations">
    <main>
        <p class="entry-p">Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro consequuntur cum deserunt ab animi dolorem nostrum reprehenderit modi consectetur quaerat, laboriosam nulla ad labore atque, eum impedit earum ea. Maxime, laboriosam labore assumenda debitis officia odio quis distinctio a repudiandae eius dignissimos nulla voluptatibus, sunt cum eum illo voluptates rem sequi. Ad culpa impedit minus consequatur! Rerum natus deleniti assumenda laboriosam dolore veniam nesciunt sit labore odit, ipsum provident dolores totam iste ex aliquid distinctio nobis necessitatibus tempora, repellendus commodi. Pariatur maiores deserunt aspernatur assumenda sequi rem minus. Culpa necessitatibus nostrum officiis adipisci fuga animi eos, mollitia quia dolor, dignissimos a architecto est reiciendis distinctio rerum voluptatibus enim explicabo. Nam officiis expedita labore provident dolor vel minus rerum, cumque qui voluptatem cum totam distinctio maxime debitis neque voluptas quibusdam id blanditiis. Et nam pariatur a! Distinctio voluptatibus optio architecto corrupti nobis eaque perspiciatis et vitae. Quam laborum ipsa rem magnam, voluptates quos velit architecto dignissimos incidunt mollitia? Nesciunt quia, ipsam doloribus repudiandae repellat adipisci eveniet quam minus consectetur molestias perferendis, distinctio, itaque error placeat. Dignissimos minima impedit est itaque consequuntur magnam in reiciendis sit dolorum sed, aliquid cum quae quod officia dolores iure praesentium nam vitae. Culpa cumque possimus unde.</p>
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
        width: 90%;
    }

    p {
        text-align: justify;
    }

    img {
        max-width: 100%;
    }
</style>