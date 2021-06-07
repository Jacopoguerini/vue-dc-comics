<template>
  <section>

    <div class="container">

        <div v-for="(element, index) in elements" :key="index" class="column">
            <div class="image">
                <img :src="'../assets/img/' + element.url" alt=""/>
            </div>
            <h4>{{ element.text }}</h4>
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
                    url: 'buy-comics-digital-comics.png'
                },
                {
                    text: "merchandise",
                    url: 'buy-comics-merchandise.png'
                },
                {
                    text: "subscription",
                    url: 'buy-comics-subscriptions.png'
                },  
                {
                    text: "dc power visa",
                    url: 'buy-dc-power-visa.svg'
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
        width: 40px;
    }

    img {
        height: 40px;
        margin: 0 15px;
    }

    h4 {
        font-size: 12px;
        font-weight: 400;
        text-transform: uppercase;
    }

</style>