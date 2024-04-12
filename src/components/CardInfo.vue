<script>
export default{
    name: 'CardInfo',
    props: ['image', 'title']
}
</script>

<template>
        <div class="card">
            <div class="card-img">
                <img :src="image" alt="">
            </div>
            <div class="text-card">
                {{ title }}
            </div>
        </div>
        
    
</template>

<style scoped lang="scss">


.card{
    width: calc((100% / 6) - 10px);

    .card-img{
        width: 110px;
        height: 110px;

        img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        }
    }
    

    .text-card{
        color: white;
        font-size: 12px;
    }
}

    





</style>