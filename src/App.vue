<script>
export default{
data(){
return{
    check_mark: true,
    visible: true,
}
},
methods: {
Smeshariki: function () {
    this.check_mark = false;
    this.visible = !this.visible;
},
}
}
</script>

<template>
<input class="text-field__input" type="checkbox" v-model="check_mark"> 
<button @click="Smeshariki">Smeshariki</button>
<p v-if="visible">{{ check_mark ? 'Pin' : 'Krosh' }}</p>
</template>

<style>
</style>