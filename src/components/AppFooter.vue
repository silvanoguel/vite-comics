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

// .footer-logo img {
//     width: 600px;
// }

.footer-down {
    height: 180px;
    background-color: #303030;
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

</style>