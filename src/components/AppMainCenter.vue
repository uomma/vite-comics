<script>
export default {
    name: 'AppMainCenter'
}

</script>
<template>
    <ul>
        <li><img src="/buy-comics-digital-comics.png    " alt=""><a href="#">DIGITAL COMICS</a></li>
        <li><img src="/buy-comics-merchandise.png    " alt=""><a href="#">DC MERCHANDISE</a></li>
        <li><img src="/buy-comics-subscriptions.png    " alt=""><a href="#">SUBSCRIPTION</a></li>
        <li><img src="/buy-comics-shop-locator.png    " alt=""><a href="#">COMIC SHOP LOCATOR</a></li>
        <li><img src="/buy-dc-power-visa.svg    " alt=""><a href="#">DC POWER VISA</a></li>

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

        }

    }
}
</style>
