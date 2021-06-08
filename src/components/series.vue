<template>
    <div class="series">
        <img :src="item.thumb" alt="">
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
        clear: both;
        width: calc((100% / 6) - 20px);
        margin: 10px 0;
    }

    img {
        max-width: 100%;
    }

</style>