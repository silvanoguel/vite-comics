<script>
export default {
    name: "HeroesCard",
    props: {
        image: String,
        title: String,
    }
}
</script>

<template>
    <div class="card">
        <img :src="image" alt="">
        <p>{{ title }}</p>
    </div>
</template>


<style lang="scss" scoped>

.card {
    display: flex;
    flex-direction: column;
    width: calc(100% / 6 - 15px);
    margin-right: 15px;
    margin-bottom: 40px;
    img {
        width: 180px;
        height: 180px;
    }
    p {
        color: white;
        text-align: left;
        margin-top: 10px;
    }
}
</style>