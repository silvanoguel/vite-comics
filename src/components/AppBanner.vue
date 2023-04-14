<script>
export default {
    name: "AppBanner",
    props: {
        title: String,
        image: String,
    }
}
</script>

<template>
    <div class="banner">
        <img src="../assets/img/jumbotron.jpg" alt="">
        <h3> {{ title }}</h3>
    </div>
</template>


<style scoped>

.banner {
    margin-top: 20px;
    position: relative;
    width: 100%;
    height: 400px;
}

img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: top;
}

h3 {
    position: absolute;
    left: 16%;
    transform: translate(-50%, -50%);
    background-color: #0282F9;
    color: white;
    padding: 10px 20px;
}

</style>