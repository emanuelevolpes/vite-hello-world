<script>
export default {
    data() {
        return {
            message: 'La mia prima app con Vite!'
        }
    }
}
</script>

<template>
    <div class="container">
        <h1>{{ message }}</h1>
    </div>
</template>

<style scoped>
.container {
    background-color: aqua;
    border-radius: 8px;
}

h1 {
    text-align: center;
    margin: 0;
}
</style>