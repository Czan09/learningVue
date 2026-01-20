<template>
    <div class="about">
        <h1>About Us</h1>
        <p>Welcome to our Vue.js application. This is the About page where you can learn more about our project.</p>
        
        <section class="features">
            <h2>Features</h2>
            <ul>
                <li>Fast and reactive UI with Vue.js</li>
                <li>Component-based architecture</li>
                <li>Easy to navigate and user-friendly</li>
            </ul>
        </section>

        <section class="contact">
            <h2>Get in Touch</h2>
            <p>Have questions? Feel free to reach out to us.</p>
        </section>
    </div>
</template>

<script>
export default {
    name: 'About',
    data() {
        return {
            appName: 'My Vue App'
        }
    }
}
</script>

<style scoped>
.about {
    padding: 2rem;
    max-width: 800px;
    margin: 0 auto;
}

h1 {
    color: #333;
    margin-bottom: 1.5rem;
}

section {
    margin: 2rem 0;
}

h2 {
    color: #555;
    margin-top: 1.5rem;
    margin-bottom: 1rem;
}

ul {
    list-style-position: inside;
    line-height: 1.8;
}

p {
    color: #666;
    line-height: 1.6;
}
</style>