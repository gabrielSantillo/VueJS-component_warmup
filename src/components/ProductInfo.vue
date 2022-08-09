<template>
    <div class="father_div">
        <div class="first_div">
            <h2>The first Avenger</h2>
            <p>Captain America: The First Avenger is a 2011 American superhero film based on the Marvel Comics character Captain America. Produced by Marvel Studios and distributed by Paramount Pictures,[N 1] it is the fifth film in the Marvel Cinematic Universe (MCU). The film was directed by Joe Johnston, written by Christopher Markus and Stephen McFeely, and stars Chris Evans as Steve Rogers / Captain America alongside Tommy Lee Jones, Hugo Weaving, Hayley Atwell, Sebastian Stan, Dominic Cooper, Neal McDonough, Derek Luke, and Stanley Tucci. During World War II, Steve Rogers, a frail man, is transformed into the super-soldier Captain America and must stop the Red Skull (Weaving) from using the Tesseract as an energy source for world domination.</p>
        </div>

        <div>
            <h2>Now in the IMAX</h2>
            <iframe width="460" height="315" src="https://www.youtube.com/embed/6y3oHJnfnjU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>

        <product-gallery></product-gallery>
    </div>
</template>

<script>
import ProductGallery from '@/components/ProductGallery.vue'
    export default {
        components: {
            ProductGallery
        }
    }
</script>

<style scoped>

.father_div {
    margin-top: 50px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    column-gap: 25px;
}

iframe {
    border-radius: 5px;
}

.first_div {
    text-align: start;
    margin-left: 10px;
}

</style>