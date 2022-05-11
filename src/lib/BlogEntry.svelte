<script>
    export let title = "Título"
    export let date = "7 de mayo de 2022"
    export let imgPath = ""
    export let imgAlt = ""
    export let link = "#"
</script>
<div class="container">
    <div class="img-container">
        <img src="{imgPath}" alt="{imgAlt}">
    </div>
    <a href="{link}" class="title">
        <span>{title}</span>
        <p class="date">{date}</p>
    </a>
</div>

<style>
    .container {
        width: 100%;
        max-width: 100%;
        height: 85vh;
        max-height: 85vh;
        display: flex;
        flex-direction: column;
    }

    .img-container {
        width: 100%;
        height: 100%;
        overflow: hidden;
        position: relative;
    }
    img {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        height: 100%;
        width: auto;
    }

    span {
        font-size: 2.5rem;
        font-weight: bold;
        font-family: 'Montserrat', sans-serif;
        text-decoration: none;
    }
    a {
        padding-top: 2rem;
        padding-bottom: 2rem;
        width: 100%;
        color: #000;
        text-decoration: none;
    }

    p {
        font-family: 'Roboto', sans-serif;
    }

    @media screen and (min-width: 700px) {
        .container {
            flex-direction: row;
            align-items: center;
            justify-content: space-between;
        }
        a {
            padding-left: 4rem;
            padding-right: 4rem;
        }
    }
</style>