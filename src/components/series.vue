<template>
    <div class="series">
        <img :src="item.thumb" :alt="item.series">
        <h2>{{ item.series }}</h2>
    </div>
</template>

<script>
export default {
    name: "Series",
    props: ["item"] //  
}
</script>

<style lang="scss" scoped>

    .series {
        width: 180px;
        height: 250px;
    }

    img {
        width: 100%;
        height: 180px;
        object-fit: cover;
        object-position: top;
        cursor: pointer;
    }

    h2 {
        display: block;
        color: white;
        font-size: 12px;
        text-transform: uppercase;
        margin-top: 15px;
        word-wrap: break-word;
    }

</style>