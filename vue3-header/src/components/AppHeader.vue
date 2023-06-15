<template>
    <navbar id="header-navbar">
        <h1>My Ugly Navbar</h1>
        <ul>
            <li v-for="link in links"><a :href="link.link">{{ link.name }}</a></li>
        </ul>
    </navbar>
</template>
<script>
export default {
    name: 'AppHeader',
    data() {
            return {
                links: [
                    {
                        name: 'Home',
                        link: '#'
                    },
                    {
                        name: 'Prodotti',
                        link: '#'
                    },
                    {
                        name: 'Contatti',
                        link: '#'
                    }
                ]
            }
        },
}
</script>
<style lang="scss" scoped>
    
</style>