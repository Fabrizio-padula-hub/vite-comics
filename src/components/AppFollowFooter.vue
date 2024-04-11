<script>
export default{
    name: 'AppFollowFooter',
}
</script>

<template>
    <section class="bg-gray">
        <div class="big-wrapper">
            <div>
                <button class="btn">SIGN-UP NOW!</button>
            </div>
            <div class="follow-icons">
                <span>FOLLOW US</span>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">

            </div>
        </div>
        
        
        
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as*;

.bg-gray{
    background-color: #303030;
    min-height: 70px;
    display: flex;
    align-items: center;
    
    .big-wrapper{
        display: flex;
        justify-content: space-between;
        align-items: center;

        .btn{
            color: white;
            border-color: #0482f9;
            background-color: #303030;
            padding: 10px;
            cursor: pointer;
        }

        .follow-icons{
            display: flex;
            align-items: center;

            span{
                color: #0482f9;
                margin-right: 15px;
            }

            img{
                margin-left: 8px;
                max-height: 26px;
            }
        }
    }
}



</style>