<template>
    <main>
        <div class="card-container">
            <div v-for="(card,i) in cards" :key="i">
                <div class="card" >
                    <img :src="card.thumb" alt="">
                </div>
                <p>{{card.type}}</p>
            </div>
            
        </div>
    </main>
</template>

<script>
export default {
    props:{
        cards:Array
    }
}
</script>

<style lang="scss" scoped>
    main{
        width: 100%;
        height: 600px;
        background-color:black ;
        .card-container{
            width: 1020px;
            display: flex;
            margin: 0 auto;
            column-gap: 20px;
            flex-wrap: wrap;
            padding-top: 70px;
            div{
                margin-bottom: 30px;
                .card{
                width: 150px;
                height: 150px;
                border: 2px solid white;
                margin-bottom: 10px;
                img{
                    width: 100%;
                    height: 100%;
                    object-fit: cover;
                }
            }
            p{
                    text-transform: uppercase;
                    color: white;
                }
            }
        }
    }
</style>