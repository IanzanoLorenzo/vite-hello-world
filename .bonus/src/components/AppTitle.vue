<script>
export default {
    data() {
        return {
            welcomeMsg: 'La mia Prima app con Vite!'
        }
    },
}
</script>
<template>
    <div>
        <h1 v-text="welcomeMsg"></h1>
    </div>
</template>
<style scoped>
    h1{
        text-align: center;
    }
</style>