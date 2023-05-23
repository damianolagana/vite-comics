<script>
export default {
    components: {

    },
    data() {
        return {
            Icons: [
                {
                    imgIcon: "../assets/img/buy-comics-digital-comics.png",
                    title: "DIGITAL COMICS"
                },
                // {
                //     imgIcon: "my-vue-app\src\assets\img\buy-comics-merchandise.png",
                //     title: "DC MERCHANDISE"
                // },
                // {
                //     imgIcon: "my-vue-app\src\assets\img\buy-comics-subscriptions.png",
                //     title: "SUBSCRIPTION"
                // },
                // {
                //     imgIcon: "my-vue-app\src\assets\img\buy-comics-shop-locator.png",
                //     title: "COMIC SHOP LOCATOR"
                // },
                // {
                //     imgIcon: "my-vue-app\src\assets\img\buy-dc-power-visa.png",
                //     title: "DC POWER VISA"
                // },
            ]
        }
    },

}
</script>

<template>
    <div class="container">
        <div v-for="icon in Icons">
            <img :src="icon.imgIcon" alt="">
            <h3>{{ icon.title }}</h3>
        </div>

    </div>
</template>

<style scoped></style>