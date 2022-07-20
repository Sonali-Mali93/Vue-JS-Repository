<template>
    <hr>
    <h1>Two way data Binding</h1>
    <input type="text" v-model="data" />
    <h2>{{ data }}</h2>
</template>
<script>
export default {
    name: 'DataBinding',
    data() {
        return {
            data: 200
        }
    }
}
</script>