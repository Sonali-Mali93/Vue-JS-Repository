<template>
    <hr>
    <h1>Get the Input value</h1>
    <input type="text" placeholder="Enter your email" v-model="email">
    <br><br>
    <input type="password" placeholder="Enter your password" v-model="password">
    <br><br>
    <button type="button" v-on:click="getData()">Get Data</button>
    <p>{{ email }}{{ password }} </p>
</template>
<script>
export default {
    name: "InputValues",
    data() {
        return {
            email: null,
            password: null
        }
    },
    methods: {
        getData() {
            console.log("Values : ", this.email, this.password)
        }
    }
}
</script>
<style>
hr {
    border: 1px solid orangered;
}
</style>