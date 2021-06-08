<template>
    <div class="series">

    </div>
</template>

<script>
export default {
    name: "Series",
    props: ["element"]
}
</script>

<style lang="scss" scoped>

    .series {
        height: 50px;
        width: calc((100% / 6) - 20px);
        background-color: red;
        margin: 10px 0;
    }

</style>