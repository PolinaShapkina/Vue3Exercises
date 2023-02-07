<script>
export default{
data(){
return{
    isDisabled: true,
    isDisabled1: true,
    checked: false,
}
},
methods: {
Smeshariki: function () {
    this.isDisabled = false;
},
smeshariki: function () {
    this.isDisabled1 = false;
},
}
}
</script>

<template>
<input type="text" class="text-field__input"  v-bind:disabled="isDisabled">
<br>
<button @click="Smeshariki">Smeshariki</button>
<br>
<br>
<br>
<input type="text" class="text-field__input" v-bind:disabled="isDisabled1">
<br>
<input type="checkbox" v-model="checked" @click="smeshariki">
<button @click="Smeshariki">Smeshariki</button> 
</template>

<style>
</style>