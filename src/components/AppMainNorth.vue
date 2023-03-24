<script>
export default {
    name: 'AppMainNorth',
}
</script>
<template>
    <div class="faquel">
        <div class="up"></div>
        <div class="down">container</div>
    </div>
</template>
<style lang="scss" scoped>
@use '../styles/variables.scss' as *;
@use '../styles/mixins' as *;


div {
    background-color: black;
    color: $text-color;

    .up {
        @include bgJumbo('../public/jumbotron.jpg');
        height: 350px;
    }

    .down{
        height: 500px;
    }

}
</style>