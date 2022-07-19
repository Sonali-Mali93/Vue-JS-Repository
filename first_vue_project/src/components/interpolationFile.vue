<template>
    <h1>{{a =90099}}</h1>
    <p><b>email:</b> {{ email}}</p>
    <p><b>Mobile No :</b> {{mobileNo}}</p>
    <p>Name: {{name}}</p>
    <h6>getValue: {{ getValue(78)}}</h6>
    <p>displayData = {{displayData()}}</p>
    <p>accessing property from another component= {{displayData().studentName}}</p>
   

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
    },
    methods:{
        displayData(){
            return {
                studentName : "Mayur",
                StudEmail : "email",
                number : this.mobileNo
            }
        }
    }
}
</script>

<style scoped>
h1{
    color: orange;
}
</style>