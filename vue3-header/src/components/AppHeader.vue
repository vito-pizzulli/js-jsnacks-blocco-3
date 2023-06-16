<template>
    <navbar id="header-navbar">
        <h1>My Ugly Navbar</h1>
        <ul>
            <NavLink v-for="link in links" 
                :navElement="link"
            />
        </ul>
    </navbar>
</template>
<script>
import NavLink from './NavLink.vue';
export default {
    name: 'AppHeader',
    components: {
        NavLink
    },
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