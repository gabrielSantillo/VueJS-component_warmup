<template>
    <div class="father_div">
        <div class="first_div">
            <div>
            <h2>The Avengers</h2>
            <iframe width="315" height="315" src="https://www.youtube.com/embed/eOrNdBpGMv8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>

            <div>
            <h2>Avengers: Age of Ultron</h2>
            <iframe width="315" height="315" src="https://www.youtube.com/embed/tmeOjFno6Do" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"  allowfullscreen></iframe>
            </div>
        </div>
    

        <div class="first_div">
            <div>
                <h2>Avengers: Infinity War</h2>
                <iframe width="315" height="315" src="https://www.youtube.com/embed/6ZfuNTqbHE8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>

            <div>
                <h2>Avengers: End Game</h2>
                <iframe width="315" height="315" src="https://www.youtube.com/embed/TcMBFSGVi1c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
    </div>

    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

.father_div {
    display: grid;
    grid-template-rows: 1fr 1fr;
    width: 100%;
    margin-top: 50px;
}

.first_div {
    display: grid;
    grid-template-columns: 1fr 1fr;
    margin-bottom: 50px;
}

iframe {
    border-radius: 5px;
}

</style>