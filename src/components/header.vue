<template>
    <header>
       <div class="container">
            <!-- logo -->
            <a href="#">
               <img src="../assets/img/dc-logo.png" alt="">
            </a>
            <!-- /logo -->

            <!-- nav -->
            <nav>
                <ul class="list-inline">
                    <li v-for="(link, index) in links" :key="index">
                        <a href="link.url">{{ link.text }}</a>
                    </li>
                </ul>
            </nav>
            <!-- /nav -->
       </div>
    </header>
</template>

<script>
export default {
    name: "Header",
    data: function () {
        return {
            links: [
                {
                    text: "characters",
                    url: "#characters",
                    current: false
                },
                {
                    text: "comics",
                    url: "#comics",
                    current: true
                },
                {
                    text: "movies",
                    url: "#movies",
                    current: false
                },
                {
                    text: "tv",
                    url: "#tv",
                    current: false
                },
                {
                    text: "games",
                    url: "#games",
                    current: false
                },
                {
                    text: "collectibles",
                    url: "#collectibles",
                    current: false
                },
                {
                    text: "videos",
                    url: "#videos",
                    current: false
                },
                {
                    text: "fans",
                    url: "#fans",
                    current: false
                },
                {
                    text: "news",
                    url: "#news",
                    current: false
                },
                {
                    text: "shop",
                    url: "#shop",
                    current: false
                }
            ]
        }
    }

}
</script>

<style lang="scss" scoped>
    header {
        height: 140px;
    }

    .container {
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    img {
        width: 80px;
        height: 80px;
    }

    a {
        text-transform: uppercase;
    }

</style>