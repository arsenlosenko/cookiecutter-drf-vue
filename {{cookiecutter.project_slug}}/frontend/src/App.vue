<template>
    <div>
        <router-link to="/home">Home</router-link> |
        <router-link to="/about">About</router-link>
        <router-view/>
    </div>
</template>

<script>

export default {
    name: 'app',
};
</script>

<style>
</style>

