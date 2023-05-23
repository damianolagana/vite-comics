<script>
export default {
    components: {

    },
    data() {
        return {
            Icons: [
                {
                    imgIcon: "/img/buy-comics-digital-comics.png",
                    title: "DIGITAL COMICS"
                },
                {
                    imgIcon: "/img/buy-comics-merchandise.png",
                    title: "DC MERCHANDISE"
                },
                {
                    imgIcon: "/img/buy-comics-subscriptions.png",
                    title: "SUBSCRIPTION"
                },
                {
                    imgIcon: "/img/buy-comics-shop-locator.png",
                    title: "COMIC SHOP LOCATOR"
                },
                {
                    imgIcon: "/img/buy-dc-power-visa.svg",
                    title: "DC POWER VISA"
                },
            ]
        }
    },

}
</script>

<template>
    <div class="container d-flex">
        <div v-for="icon in Icons">
            <img :src="icon.imgIcon" alt="">
            <h3>{{ icon.title }}</h3>
        </div>

    </div>
</template>

<style scoped></style>