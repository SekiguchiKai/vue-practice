<template>
    <p class="message">{{msg}}</p>
</template>

<script>
    export default {
        data() {
            return {msg: 'hello Vue!'};
        }
    }
</script>

<style scoped>
    .message{color: aqua}
</style>