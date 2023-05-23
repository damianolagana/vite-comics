<script>
export default {
    components: {

    },
    data() {
        return {
            links: [
                "CHARACTERS",
                "COMICS",
                "MOVIES",
                "TV",
                "GAMES",
                "COLLECTIBLES",
                "VIDEOS",
                "FANS",
                "NEWS",
                "SHOP",
            ]

        }
    }
}



</script>

<template>
    <header>
        <nav class="navbar bg-light">
            <div class="container">
                <a class="navbar-brand" href="#">
                    <img src="../assets/img/dc-logo.png" alt="Bootstrap" width="30" height="24">
                </a>
                <div class="d-flex justify-content-sm-between">
                    <a v-for="link in links" href="">{{ link }}</a>
                </div>
            </div>

        </nav>
    </header>
</template>

<style scoped>
header {
    height: 120px;
}

nav {
    height: 100%;
}

a {
    text-decoration: none;
    color: black;
}

a>img {
    width: 60px;
    height: 60px;
}

.container>div {
    width: 60%;
}
</style>