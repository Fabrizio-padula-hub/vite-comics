<script>
export default{
    name: 'AppInfoFooter',
}
</script>

<template>
    <section class="bg-comics">
        <div class="big-wrapper">
            <!-- container info dc comics e shop -->
            <div class="container-info-sx">
                <div class="info-comics">
                    <h4>DC COMICS</h4>
                    <ul>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                        <li>characters</li>
                    </ul>
                </div>
                <div class="info-shop">
                    <h4>SHOP</h4>
                    <ul>
                        <li>Shop DC</li>
                        <li>Shop DC</li>
                    </ul>
                </div>
            </div>
            <!-- /container info dc comics e shop -->
            <!-- container info dc e site -->
            <div class="container-info-dx">
                <div class="info-dc">
                    <h4>DC</h4>
                    <ul>
                        <li>Terms Of Use</li>
                        <li>Terms Of Use</li>
                        <li>Terms Of Use</li>
                        <li>Terms Of Use</li>
                        <li>Terms Of Use</li>
                        <li>Terms Of Use</li>
                        <li>Terms Of Use</li>
                        <li>Terms Of Use</li>
                        <li>Terms Of Use</li>
                        <li>Terms Of Use</li>
                        <li>Terms Of Use</li>
                    </ul>
                </div>
                <div class="info-sites">
                    <h4>SITES</h4>
                    <ul>
                        <li>MAD Magazine</li>
                        <li>MAD Magazine</li>
                        <li>MAD Magazine</li>
                        <li>MAD Magazine</li>
                        <li>MAD Magazine</li>
                    </ul>
                </div>
            </div>
            <!-- /container info dc e site -->
        </div>
    </section>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as*;

h4{
    margin-bottom: 8px;
    margin-right: 20px;
}

li{
    font-size: 11px;
    color: #797979;
    padding-bottom: 4px;
    margin-right: 24px;
}


.bg-comics{
    background-image: url(../assets/img/footer-bg.jpg);
    color: white;

    .big-wrapper{
        display: flex;
        background-image: url(../assets/img/dc-logo-bg.png);
        background-repeat: no-repeat;
        background-position: 100%;
       padding: 30px 0;
    }

    .container-info-dx{
        display: flex;
    }

}


</style>