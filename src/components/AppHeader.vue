<script>
export default{
    name: 'AppHeader'
}

</script>

<template>
    <section class="align-center big-wrapper">
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>

        <nav>
            <ul>
                <li>
                    <a href="#">home</a>
                </li>
                <li>
                    <a class="active" href="#">home</a>
                </li>
                <li>
                    <a href="#">home</a>
                </li>
                <li>
                    <a href="#">home</a>
                </li>
                <li>
                    <a href="#">home</a>
                </li>
                <li>
                    <a href="#">home</a>
                </li>
                <li>
                    <a href="#">home</a>
                </li>
                <li>
                    <a href="#">home</a>
                </li>
                <li>
                    <a href="#">home</a>
                </li>
                <li>
                    <a href="#">home</a>
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
