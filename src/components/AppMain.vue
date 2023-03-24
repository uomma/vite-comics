<script>
import AppMainNorth from './AppMainNorth.vue';
import AppMainCenter from './AppMainCenter.vue';
import AppMainSouth from './AppMainSouth.vue';


export default{
    name: 'AppMain',
    components:{
        AppMainNorth,
        AppMainCenter,
        AppMainSouth,
    }
}
</script>
<template><main>
    <AppMainNorth></AppMainNorth>
    <AppMainCenter></AppMainCenter>
    <AppMainSouth></AppMainSouth>
</main></template>