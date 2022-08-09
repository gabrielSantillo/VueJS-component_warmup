<template>
    <div class="father_div">
        <div class="first_div">
            <h1>Captain America</h1>
            <p>The most powerful Avenger</p>
            <p>The first Avenger</p>
        </div>

        <div class="sun_divs">
          <img src="https://m.media-amazon.com/images/M/MV5BMTY4NTU1NTEwNV5BMl5BanBnXkFtZTcwMzE1NzAwNg@@._V1_.jpg" alt="">
        </div>

        <div class="sun_divs">
            <img src="https://cf-images.us-east-1.prod.boltdns.net/v1/static/5359769168001/0a823cb0-01a9-4835-a348-c64187783ccb/d37cb96c-805c-4aa2-9f2f-e62d9eb814c7/1280x720/match/image.jpg" alt="">
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
    grid-template-columns: 1fr 1fr 1fr;
    column-gap: 5px;
}

.first_div {
    color: rgb(5, 5, 145);
    display: grid;
}

img {
    width: 350px;
    height: 350px;
    object-fit: cover;
    border-radius: 5px;
}

</style>