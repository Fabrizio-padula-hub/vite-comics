<script>
export default{
    name: 'AppHeader',
    data(){
        return{
            links: [
                {
                    text: 'CHARACTERS',
                    active: false
                },
                {
                    text: 'COMICS',
                    active: true
                },
                {
                    text: 'MOVIES',
                    active: false
                },
                {
                    text: 'TV',
                    active: false
                },
                {
                    text: 'GAMES',
                    active: false
                },
                {
                    text: 'COLLECTIBLES',
                    active: false
                },
                {
                    text: 'VIDEOS',
                    active: false
                },
                {
                    text: 'FANS',
                    active: false
                },
                {
                    text: 'NEWS',
                    active: false
                },
                {
                    text: 'SHOP',
                    active: false
                },
                
            ],
        }
    }
}


</script>

<template>
    <section class="align-center big-wrapper">
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>

        <nav>
            <ul>
                <li v-for="singleLink in links">
                    <a :class="{ 'active': singleLink.active }" href="#">{{ singleLink.text }}</a>
                </li>
            </ul>
        </nav>
    </section>

</template>

<style scoped lang="scss">
@use '../style/partials/variables' as*;

.align-center{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px;
}
.logo{
    max-width: 50px;
}
nav{
    ul{
        display: flex;
    }
    

    a{
        color: black;
        padding: 10px;
        font-size: 13px;

        &.active{
            color: $bg-primary;
        }
    }
}


</style>
