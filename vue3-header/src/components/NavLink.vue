<template>
    <div>
        <li><a :href="navElement.link">{{ navElement.name }}</a></li>
    </div>
</template>
<script>
export default {
    name: 'NavLink',
    props: {
        navElement : Object
    }
}
</script>
<style lang="scss">
    
</style>