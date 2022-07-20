<template>
    <hr>
    <label for="Mango">Mango</label>
    <input type="checkbox" value="mango" v-model="fruits" id="Mango">

    <label for="Banana">Banana</label>
    <input type="checkbox" value="Banana" v-model="fruits" id="Banana">

    <label for="Apple">Apple</label>
    <input type="checkbox" value="Apple" v-model="fruits" id="Apple">
    <br><br>
    <h4>Fruits name : {{ fruits }}</h4>

    <h3>Profession</h3>
    <label for="student">Student</label>
    <input type="radio" value="student"  id="student"   v-model="profession" name="profession">

    <label for="developer">Developer</label>
    <input type="radio" value="developer"  id="developer"  v-model="profession" name="profession">

    <h4>Profession : {{ profession }}</h4>

</template>
<script>
export default {
    name: 'RadioAndCheckboxInputValue',
    data() {
        return {
            fruits: [],
            profession : null
        }
    }
}
</script> 