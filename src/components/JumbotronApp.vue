<template>
    <div class="jumbo">
        <div class="current-series">CURRENT SERIES</div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    .jumbo{
        width: 100%;
        height: 300px;
        background-image: url(../assets/jumbotron.jpg);
        background-size: cover;
        position: relative;
        .current-series{
            position: absolute;
            width: 160px;
            height: 40px;
            line-height: 40px;
            color: white;
            background-color: rgb(82, 124, 214);
            font-weight: 900;
            text-align: center;
            bottom: -20px;
            left: 240px;
        }
    }
</style>