<template>
    <div class="top-footer">
        <div class="buy-card">
            <img src="..\assets\buy-comics-digital-comics.png" alt="">
            <p>DIGITAL COMICS</p>
        </div>
        <div class="buy-card">
            <img src="..\assets\buy-comics-merchandise.png" alt="">
            <p>DC MERCHANDISE</p>
        </div>
        <div class="buy-card">
            <img src="..\assets\buy-comics-subscriptions.png" alt="">
            <p>SUBSCRIPTION</p>
        </div>
        <div class="buy-card">
            <img src="..\assets\buy-comics-shop-locator.png" alt="">
            <p>COMIC SHOP LOCATOR</p>
        </div>
        <div class="buy-card">
            <img src="..\assets\buy-dc-power-visa.svg" alt="">
            <p>DC POWER VISA</p>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    .top-footer{
        background-color: rgb(55, 55, 182);
        width: 100%;
        height: 120px;
        display: flex;
        justify-content: center;
        gap: 60px;
        position: relative;
        .buy-card{
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 10px;
            color: white;
            img{
                width: 40px;
                height: 50px;
            }
        }
    }
</style>