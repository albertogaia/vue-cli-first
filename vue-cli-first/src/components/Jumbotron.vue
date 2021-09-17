<template>
    <div class="hero">
        <h2>
            Sei pronto per un viaggio indimenticabile?
        </h2>
        <button>Scopri le nostre mete</button>
    </div>
</template>

<script>
export default {
    name: 'Jumbotron'
}
</script>

<style scoped>
    .hero{
        width: 100%;
        height: 400px;
        background-image: url('../assets/hero.jpg');
        background-size:cover;
        background-repeat: no-repeat;
        background-position-y: 50%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    h2{
        color: whitesmoke;
        text-shadow: 1px 1px 4px #333;
        font-size: 32px;
    }
    button {
        border: none;
        padding: 10px 20px;
        text-transform: uppercase;
        font-weight: 600;
        box-shadow: 3px 3px 0px rgb(72, 119, 177);
        transition: 0.5s;

    }
    button:hover {
        transition: 0.5s;
        cursor: pointer;
        color: rgb(72, 119, 177);
        box-shadow: 10px 10px 0px rgb(72, 177, 102);

    }
</style>