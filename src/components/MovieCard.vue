<script setup>
defineProps({
    img: {
        type: String,
        required: true
    },
    title: {
        type: String,
        required: true
    },
    rating: {
        type: Number,
        required: false,
        default: -1
    }
})
</script>
<template>
    <div class="movie-container">
        <div class="img-cont">
            <img :src="img">
        </div>
        <span class="title">{{ title }}</span>
        <span class="rating">{{ rating < 0 ? "Sin valoraciones" : `${rating}/10`}}</span>
    </div>
</template>

<style>
    .movie-container{
        width: 100%;
        display: flex;
        flex-direction: column;
        overflow: hidden;
    }

    img{
        width: 100%;
    }

    .title{
        margin-top: .5em;
        text-align: center;
        text-overflow: ellipsis;
        white-space: nowrap;
        overflow: hidden;
        max-width: 100%;
        font-weight: 700;
        color: #f2f2f2;
    }

    .rating{
        color: rgb(233, 218, 12);
    }
</style>