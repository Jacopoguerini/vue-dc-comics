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
        margin: 10px 0;
    }

    img {
        width: 180px;
        height: 180px;
        object-fit: cover;
        object-position: top;
    }

</style>