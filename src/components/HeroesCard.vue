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
    <div class="card" :class="type">
        <img :src="image" alt="">
        <h4>{{ title }}</h4>
    </div>
</template>


<style lang="scss" scoped>

.card {
    width: calc(100% / 4 - 10px);
    margin: 5px;
    background-color: white;
    padding: 10px;
    h4 {
        color: black;
    }
}
</style>