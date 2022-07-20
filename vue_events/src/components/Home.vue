<template>
    <h1 v-on:mousemove="mouse_click()">Home Componet</h1>
    <button v-on:click="getDate()">Click Here to increase count</button>
    <button v-on:dblclick="test()">CLICK ME</button>
    <h1 v-on:focusout="mouse_click()">CLICK ME</h1>
    <p>{{ count }}</p>
    <p></p>
</template>
<script>
export default {
    name: "HomeComponent",
    data() {
        return {
            count : 0,
        }
    },
    methods: {
        getDate() {
            this.count = this.count - 1
        },
        test() {
            alert("Dobule click event is called")
        },
        mouse_click() {
            console.log("ok")
        }
    }
}
</script>