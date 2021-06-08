<template>
  <section>

    <div class="container">

        <div v-for="(element, index) in elements" :key="index" class="column">
            <div class="image">
                <img :src="element.url" alt=""/>
            </div>
            <div class="title">
                <h4>{{ element.text }}</h4>
            </div>
        </div>

    </div>   
  </section>
</template>

<script>
export default {
    name: "Panel",
    data: function () {
        return {
            elements: [
                {
                    text: "digital comics",
                    url: require('../assets/img/buy-comics-digital-comics.png')
                },
                {
                    text: "merchandise",
                    url: require('../assets/img/buy-comics-merchandise.png')
                },
                {
                    text: "subscription",
                    url: require('../assets/img/buy-comics-subscriptions.png')
                },  
                {
                    text: "dc power visa",
                    url: require('../assets/img/buy-dc-power-visa.svg')
                }                              
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
    @import '../style/variables.scss';

    section {
        height: 120px;
        background-color: $brandBlue;
        color: white;
    }

    .container {
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    .column {
        display: flex;
        align-items: center;
        cursor: pointer;
    }

    .image {
        height: 40px;
        width: 40px;
        margin-right: 15px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    img {
        max-width: 100%;
        max-height: 100%;
    }

    h4 {
        font-size: 12px;
        font-weight: 400;
        text-transform: uppercase;
    }

</style>