<template>
    <div class="home">
        <h1>Welcome to Your Vue App</h1>
        <p>This is the home page of your Vue application.</p>
        <router-link to="/about">Learn more about us</router-link>
    </div>
</template>

<script>
export default {
    name: 'Home'
}
</script>

<style scoped>
.home {
    text-align: center;
    margin-top: 50px;
}
</style>