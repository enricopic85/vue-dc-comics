<template>
    <nav>
        <img src="../assets/dc-logo.png" alt="">
        <ul>
            <li>CHARACTERS</li>
            <li>COMICS</li>
            <li>MOVIES</li>
            <li>TV</li>
            <li>GAMES</li>
            <li>COLLECTIBLES</li>
            <li>VIDEOS</li>
            <li>FANS</li>
            <li>NEWS</li>
            <li>SHOP</li>
        </ul>
    </nav>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,200;1,300;1,400;1,500;1,600;1,700;1,900&display=swap');
    nav{
        background-color: white;
        width: 100%;
        height: 100px;
        display: flex;
        justify-content: space-around;
        align-items: center;
        img{
            width: 60px;
            height: 60px;
        }
        ul{
            display: flex;
            gap: 20px;
            height: 100px;
            line-height: 100px;
            li{
                list-style: none;
                height: 100px;
                font-family: 'Montserrat', sans-serif;
                &:hover{
                     border-bottom: 5px solid blue;
                     color: blue;
                }
            }
        }
    }
</style>