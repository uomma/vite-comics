<script>
export default {
    name: 'AppFooter'
}
</script>
<template>
    <div class="ez">
    <div>SIGN-UP NOW</div>
    
        <ul>
            <li>FOLLOW US</li>
            <li><img src="/footer-facebook.png" alt=""></li>
            <li><img src="/footer-twitter.png" alt=""></li>
            <li><img src="/footer-youtube.png" alt=""></li>
            <li><img src="/footer-pinterest.png" alt=""></li>
            <li><img src="/footer-periscope.png" alt=""></li>
        </ul>
    </div>
</template>

<style lang="scss" scoped>

@use '../styles/variables.scss' as *;


.ez{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0px 50px ;
    background-color:$foooter-color ;

    ul{
        display: flex;
        justify-content: flex-start;
        align-items: center;
        list-style: none;

        li{
            padding: 10px;
        }
    }
}

</style>