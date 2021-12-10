<template>
    <div class="jumbotron">
        <h2>
            Questo è il jumbotron
        </h2>
    </div>
</template>

<script>
    export default {
    name: 'jumbotron',
    }
</script>

<style>
/* Con scoped non funziona */
    .jumbotron {
        display: flex;
        align-items: flex-end;
        margin: 20px 0 0;
        height: 70vh;
        width: 100%;
        background-image: url("https://picsum.photos/800/450");
        background-repeat: no-repeat;
        background-size: cover;
    }
        h2 {
            position: relative;
            bottom: 10px;
            left: 10px;
            font-size: 26px;
            color: white;
            text-shadow: 0 0 5px black;
        }
</style>