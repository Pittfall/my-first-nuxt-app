<template>
    <header class="nav">
        <ul>
            <Item item="Home" nav="/"/>
            <Item item="Users" nav="/users" />
        </ul>
    </header>
</template>

<style scoped>
    .nav {
        width: 100%;
        height: 60px;
        display: flex;
        justify-content: center;
        align-content: center;
        background-color: #ccc;
    }

    ul {
        list-style: none;
        padding: 0;
        margin: 0;
        display: flex;
        justify-content: space-around;
        align-items: center;
        width: 80%;
    }
</style>

<script>
import Item from './Item.vue'

export default {
    components: {
        Item
    }
}
</script>