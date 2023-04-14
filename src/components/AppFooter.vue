<script>

export default {
 name: "AppFooter",
}

</script>


<template>


    <footer>

        <div class="footer-top">
            <div class="container">
                <div class="footer-menu">
                    <table>
                        <tr>
                            <th>DC COMICS</th>
                            <th>DC</th>
                            <th>SITES</th>
                        </tr>
                        <tr>
                            <td>Characters</td>
                            <td>Characters</td>
                            <td>Characters</td>
                        </tr>
                        <tr>
                            <td>Characters</td>
                            <td>Characters</td>
                            <td>Characters</td>
                        </tr>
                        <tr>
                            <td>Characters</td>
                            <td>Characters</td>
                            <td>Characters</td>
                        </tr>
                        <tr>
                            <td>Characters</td>
                            <td>Characters</td>
                            <td>Characters</td>
                        </tr>
                        <tr>
                            <td>Characters</td>
                            <td>Characters</td>
                            <td>Characters</td>
                        </tr>
                        <tr>
                            <td>Characters</td>

                        </tr>
                        <tr>
                            <td>Characters</td>

                        </tr>

                        <tr>
                            <th>DC COMICS</th>
                        </tr>
                        <tr>
                            <td>Characters</td>
                        </tr>
                        <tr>
                            <td>Characters</td>
                        </tr>
                        <tr>
                            <td>Characters</td>
                        </tr>

                    </table>

                </div>

                <div class="footer-logo">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>

            </div>

        </div>


        <div class="footer-down">
            <div class="container">
                <button><h3>SIGN-UP NOW !</h3></button>
                <div class="follow">
                    <div class="follow-text">
                        <span>FOLLOW US</span>
                    </div>
                    <div class="follow-icons">
                        <img src="../assets/img/footer-facebook.png" alt="">
                        <img src="../assets/img/footer-twitter.png" alt="">
                        <img src="../assets/img/footer-youtube.png" alt="">
                        <img src="../assets/img/footer-pinterest.png" alt="">
                        <img src="../assets/img/footer-periscope.png" alt="">
                    </div>
                </div>
            </div>
        </div>

    </footer>

</template>


<style scoped lang="scss">

.footer-top {
    background-image: url(../assets/img/footer-bg.jpg);
    height: 500px;
    background-repeat: no-repeat;
    background-size: cover;
    .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
}
.footer-menu th {
    color: white;
    padding-right: 40px;
    padding-bottom: 20px;
    padding-top: 20px;
}

.footer-menu td {
    color: #959595;
    padding-right: 40px;

}
.footer-down {
    padding-top: 50px;
    padding-bottom: 50px;
    background-color: #303030;
    z-index: 999;
    position: relative;
    .container {
        display: flex;
        justify-content: space-between;
    }

}
button {
    border: 2px solid #0282F9;
    background-color: #303030;
    color: white;
    padding: 10px 30px;
}

.follow {
    display: flex;
    align-items: center;
    &-text{
        color: #0282F9;
    }
}
.follow-icons img {
    margin-left: 15px;
}

</style>