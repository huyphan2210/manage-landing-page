<script setup lang="ts">
const pages = ['Pricing', 'Product', 'About Us', 'Careers', 'Community'];

</script>

<template>
    <header>
        <img src="../../assets/images/logo.svg" alt="Logo">
        <nav>
            <a v-for="page in pages" href="/">
                {{ page }}
            </a>
        </nav>
        <button type="button">Get Started</button>
    </header>
</template>

<style scoped>
header {
    display: flex;
    justify-content: space-between;
    padding-inline: 10rem;
    padding-block: 2rem;
}
</style>
