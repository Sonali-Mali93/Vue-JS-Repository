<template>
    <h1>{{a =90099}}</h1>
    <p><b>email:</b> {{ email}}</p>
    <p><b>Mobile No :</b> {{mobileNo}}</p>
    <p>Name: {{name}}</p>
    <h6>getValue: {{ getValue(78)}}</h6>
</template>

<script>
export default{
    name: 'InterpolationData',
    data(){ // Interpolation data binding
        return{
            email: "sonalimali@gmail.com",
            mobileNo : 9085857777,
            getValue(x){
                return x
            },
            name: "Sonali"
        }
    }
}
</script>

<style scoped>
h1{
    color: orange;
}
</style>