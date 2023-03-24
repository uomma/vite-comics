<script>
export default {
    name: 'AppNav',
    data() {
        return {
            menuList: [
                {
                    nome: 'CHARACTERS',
                    link: '#',
                    target: '_self'
                },
                {
                    nome: 'COMICS',
                    link: '#',
                    target: '_self'
                },
                {
                    nome: 'MOVIES',
                    link: '#',
                    target: '_self'
                },
                {
                    nome: 'TV',
                    link: '#',
                    target: '_self'
                },
                {
                    nome: 'GAMES',
                    link: '#',
                    target: '_self'
                },
                {
                    nome: 'COLLECTIBLES',
                    link: '#',
                    target: '_self'
                },
                {
                    nome: 'VIDEOS',
                    link: '#',
                    target: '_self'
                },
                {
                    nome: 'FANS',
                    link: '#',
                    target: '_self'
                },
                {
                    nome: 'NEWS',
                    link: '#',
                    target: '_self'
                },
                {
                    nome: 'SHOP',
                    link: '#',
                    target: '_self'
                },
            ]
        }
    }
}

</script>

<template>
    <nav>
        <ul>
            <li v-for="menu in menuList"><a style="text-decoration:none" :href="menu.link" :target="menu.target">{{
                menu.nome }}</a></li>


        </ul>
    </nav>
</template>

<style lang="scss" scoped>
@use '../styles/variables.scss' as *;

nav {
    ul {
        margin: 0;
        list-style: none;
        display: flex;

    }

    li {
        a {
            color: $primary-color;
            display: inline-block;
            padding: 0.625rem;

            &:hover {
               color: $secondary-color;
               
            }

        }
    }

}
</style>