<div class="quote">
    <div class="sentence">
        <img class="quote-img flip-x" src="quote.png" alt="quote sign">
        <cite>Las mejores ideas vienen como chistes. Haz tus pensamientos tan divertidos como puedas</cite>
        <img class="quote-img" src="quote.png" alt="quote sign">
    </div>
    <p class="author">David Ogilvy</p>
</div>

<style>
    
    .quote-img {
        width: 3rem;
        transform: translateY(-1.5rem)
    }

    .flip-x {
        transform: scaleX(-1) translateY(-1.5rem);
    }

    cite {
        font-family: 'Montserrat', sans-serif;
        font-style: italic;
        font-size: 1.5rem;
        width: 75%;
        text-align: center;
        padding-left: 2rem;
        padding-right: 2rem;
    }

    .sentence {
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        
    }

    .quote {
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .author {
        font-size: 1.2rem;
    }
</style>