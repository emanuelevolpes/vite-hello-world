<script>
export default {}
</script>

<template>
    <div class="container">
        <h1>Jumbotron Vite!</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum suscipit, nemo expedita vel beatae porro
            dolore architecto deserunt odit cupiditate quod quae laboriosam voluptatibus rem aliquid? Rerum veritatis
            mollitia modi!</p>
        <hr>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ab molestiae et delectus quidem libero ratione
            minus incidunt repudiandae harum excepturi? Neque, amet. Suscipit, ratione quia perferendis quo voluptatum
            quis explicabo.</p>
        <button><a href="#">Vite</a></button>
    </div>
</template>

<style scoped>
.container {
    background-color: pink;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 30px;
    border-radius: 10px;
}

hr {
    width: 100%;
}

button {
    padding: 5px 20px;
    border: none;
    background-color: blue;
    border-radius: 5px;
}

button>a {
    text-decoration: none;
    color: white;
}
</style>