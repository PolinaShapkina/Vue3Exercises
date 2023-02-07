<script>
export default{
data(){
return{
    smeshariki: '',
    Smeshariki: ['Nyusha', 'Pin', 'Krosh'],
}
},
methods: {
addSmeshariki: function () {
    this.Smeshariki.unshift(this.smeshariki);
}
}
}
</script>

<template>
<ul class="styled">
<li v-for="(item, index) in 
			Smeshariki" :key="index">
    {{ item }}
</li>
</ul>
<input class="text-field__input" v-model="smeshariki">
<br>
<button @click="addSmeshariki">add</button>
</template>

<style>
</style>