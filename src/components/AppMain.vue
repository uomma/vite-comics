<script>
import AppMainNorth from './AppMainNorth.vue';
import AppMainCenter from './AppMainCenter.vue';


export default{
    name: 'AppMain',
    components:{
        AppMainNorth,
        AppMainCenter,
    }
}
</script>
<template><main>
    <AppMainNorth></AppMainNorth>
    <AppMainCenter></AppMainCenter>
</main></template>