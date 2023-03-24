<script>
export default {
    name: 'AppMainSouth'
}
</script>

<template>
    <main>
        <div class="anelli">
            <div class="sx">
                <ul>
                    <li class="title">DC COMICS</li>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                <ul>
                    <li class="title">SHOP</li>
                    <li>Shop DC </li>
                    <li>Shop DC Collectibles</li>
                </ul>

            </div>
            <ul>
                <li class="title">DC</li>
                <li>Terms Of Use</li>
                <li>Privacy policy(new)</li>
                <li>Ad Choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscriptions</li>
                <li>Talent Workshops</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop Help</li>
                <li>Contact Us</li>
            </ul>

            <ul>
                <li class="title">SITES</li>
                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
            </ul>
        </div>
        <div class="ol"><img src="/dc-logo-bg.png" alt=""></div>

    </main>
</template>

<style lang="scss" scoped>
@use '../styles/mixins' as *;
@use '../styles/variables.scss' as *;
main {
    display: flex;
    justify-content: space-between;
    
    @include bgImg('../public/footer-bg.jpg');

    div {

        display: flex;
        justify-content: flex-end;
        align-items: center;
        align-items: flex-start;
        padding-left: 20px;
        


        img {
            height: 400px;
            bottom: -325px;
            right: 200px;
            position: absolute;
            display: none;
        }

        ul {
            list-style: none;
            margin-left: 20px;
            color: $side-ccolor;
        }

        .title {
            color: $text-color;
            font-size: large;
            font-weight: 700;
        }

        .sx {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
        }

    }
}
</style>