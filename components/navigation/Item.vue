<template>
    <li>
        <nuxt-link :to="nav">{{ item }}</nuxt-link>
    </li>
</template>

<style scoped>
    li a {
        text-decoration: none;
        color: black;
    }

    li a:hover,
    li a:hover {
        color: white;
    }
</style>

<script>
export default {
    props: ['item', 'nav']
}
</script>