<script>

export default {
 name: "AppFeatures",
}

</script>


<template>

    <div class="features">
        <div class="container">
            <ul>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <span>DC MERCHANDISE</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <span>SUBSCRIPTION</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <span>COMIC SHOP LOCATOR</span>
                </li>
                <li>
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <span>DC POWER VISA</span>
                </li>
            </ul>

        </div>

    </div>

</template>


<style scoped lang="scss">

.features {
    display: flex;
    align-items: center;
    padding: 60px;
    background-color: #0282F9;
    img {
        width: 50px;
        margin-right: 18px;
    }
}

.container ul {
    display: flex;
    justify-content: center;
    color: white;
}

.container li {
    display: flex;
    align-items: center;
    margin-left: 30px;
}


</style>