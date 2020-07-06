<template>
    <div id="app">
        <Home msg="Hello world!" />
        <Register/>
    </div>
</template>

<script>
    import Home from './components/Home.vue';
    import Register from './components/Register.vue'

    export default {
        name: 'app',
        components: {
            Home,
            Register
        }
    };
</script>

<style>
</style>

