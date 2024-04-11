<script>
export default{
    name: 'AppInfoList',
    data(){
        return{
            infoList: [
                {
                    img: 'comics-digital-comics.png',
                    text: 'DIGITAL COMICS'
                },
                {
                    img: 'comics-merchandise.png',
                    text: 'DC MERCHANDISE'
                },
                {
                    img: 'comics-subscriptions.png',
                    text: 'SUBSCRIPTION'
                },
                {
                    img: 'comics-shop-locator.png',
                    text: 'COMIC SHOP LOCATOR'
                },
                {
                    img: 'dc-power-visa.svg',
                    text: 'DC POWER VISA'
                },
            ],
        }
    },
    methods:{
        getImageUrl(name) {
	        return new URL(`../assets/img/buy-${name}`, import.meta.url).href
        }
    }
}
</script>

<template>
    <section>
        <div class="small-wrapper">
            <div v-for="singleInfo in infoList" class="card">
                <img :src="getImageUrl(singleInfo.img)" alt="">
                <span>{{singleInfo.text}}</span>
            </div>
        </div>

    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as*;

section{
    background-color: $bg-primary;
    padding: 20px 0;

    .small-wrapper{
        display: flex;
        justify-content: space-between;

        .card{
            color: white;
            display: flex;
            align-items: center;
            flex: 1;
            
            img{
                max-height: 20px;
            }
            span{
                font-size: 12px;
                padding-left: 5px;
            }
        }
    }
}
</style>