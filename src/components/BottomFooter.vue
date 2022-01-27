<template>
    <div class="bottom-footer">
        <div class="sign-up">SIGN-UP NOW!</div>
        <div class="follow-us">
            <p>FOLLOW US</p>
            <img src="..\assets\footer-facebook.png" alt="">
            <img src="..\assets\footer-twitter.png" alt="">
            <img src="..\assets\footer-youtube.png" alt="">
            <img src="..\assets\footer-pinterest.png" alt="">
            <img src="..\assets\footer-periscope.png" alt="">
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,200;1,300;1,400;1,500;1,600;1,700;1,900&display=swap');
    .bottom-footer{
        width: 100%;
        height: 100px;
        background-color: rgb(56, 53, 53);
        position: relative;
        display: flex;
        align-items: center;
        justify-content: space-around;
        .sign-up{
            width: 150px;
            border: 2px solid white;
            height: 40px;
            line-height: 40px;
            text-align: center;
            color: white;
            font-weight: 800;
           
            &:hover{
                border-top-color: blue;
                border-bottom-color: blue;
                border-left-color: rgb(28, 28, 241);
                border-right-color: rgb(28, 28, 241);
            }
        }
        .follow-us{
            display: flex;
            align-items: center;
            gap: 20px;
            margin-left: 300px;
            color: blue;
            font-weight: 900px;
            font-family: 'Montserrat', sans-serif;
            font-size: 18px;
            p{
                font-weight: 700;
            }
        }
    }
</style>