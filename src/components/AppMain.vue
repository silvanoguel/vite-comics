<script>

export default {
 name: "AppMain",
}

</script>


<template>

<main>

    <div class="container">
        <div class="content">
            <p> -- content goes here --</p>
        </div>
        
    </div>
   

</main>

</template>


<style scoped lang="scss">

main {
    margin-top: 20px;
    // debug
    height: 180px;
    background-color: #1C1C1C;
}

.content {
    color: white;
    font-size: 2rem;
    display: flex;
    align-items: center;
    line-height: 180px;
}

</style>