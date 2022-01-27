<template>
    <div class="central-footer">
        <div class="central-footer-left">
            <div class="footer-link">
            <h4>DC COMICS</h4>
            <ul>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
            </ul>
            <h4>DC COMICS</h4>
            <ul>
                <li>Characters</li>
                <li>Comics</li>
            </ul>
        </div>
        <div class="footer-link">
            <h4>DC </h4>
            <ul>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
            </ul>
        </div>
        <div class="footer-link">
            <h4>DC </h4>
            <ul>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
            </ul>
        </div>
        </div>
        <div class="central-footer-right">
            <img src="..\assets\dc-logo-bg.png" alt="">
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    .central-footer{
        width: 100%;
        height: 400px;
        background-image: url(../assets/footer-bg.jpg);
        display: flex;
        justify-content: space-around;

        .central-footer-left{
            display: flex;
            width: 450px;
            .footer-link{
            display: flex;
            color: white;
            flex-direction: column;
            width: 400px;
            margin-top: 30px;
            margin-left: 50px ;
            
            h4{
                margin-top: 10px;
                margin-bottom: 20px;
            }
            li{
                margin-bottom: 5px;
                list-style: none;
            }
        }
        }
        .central-footer-right{
            img{
                margin-top: -70px;
            }
        }
    }
</style>