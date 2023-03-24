<script>
export default {
    name: 'AppMainCenter'
}

</script>
<template>
    <ul>
        <li><a href="#" style="text-decoration:none"><img src="/buy-comics-digital-comics.png    " alt="">DIGITAL COMICS</a></li>
        <li><a href="#" style="text-decoration:none"><img src="/buy-comics-merchandise.png    " alt="">DC MERCHANDISE</a></li>
        <li><a href="#" style="text-decoration:none"><img src="/buy-comics-subscriptions.png    " alt="">SUBSCRIPTION</a></li>
        <li><a href="#" style="text-decoration:none"><img src="/buy-comics-shop-locator.png    " alt="">COMIC SHOP LOCATOR</a></li>
        <li><a href="#" style="text-decoration:none"><img src="/buy-dc-power-visa.svg    " alt="">DC POWER VISA</a></li>

    </ul>
</template>
<style lang="scss" scoped>
@use '../styles/variables.scss' as *;


ul {
    margin: 0;
    list-style: none;
    
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: $secondary-color;
    padding: 20px 0px;


    li {
        a {
            display: inline-block;
            padding: 30px;
            color: $text-color;
            display: flex;
            justify-content: center;
            align-items: center;


        }

        img {
            height: 50px;
            padding-right: 10px;
        }

    }
}
</style>
