<script>
import AppLogo from './AppLogo.vue';
import AppNav from './AppNav.vue';


export default {
    name: 'AppHeader',
    components: {
        AppLogo,
        AppNav
    }
}
</script>

<template>
    <Header>
       <AppLogo></AppLogo>
        <AppNav></AppNav>
</Header>
</template>
<style>

header{
    display:  flex;
    justify-content: space-between;
    align-items: center;
    margin: 0px 100px;
}

</style>