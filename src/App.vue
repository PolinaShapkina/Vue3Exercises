<script>
export default{
data(){
return{
    smeshariki: '',
    Smeshariki: ['Nyusha', 'Pin', 'Krosh'],
}
},
methods: {
removeSmeshariki: function (index) {
    this.Smeshariki.splice(index, 1);
}
}
}
</script>

<template>
<ul>
<li v-for="(item, index) in 
			Smeshariki" :key="index">
    {{ item }}
    <br>
    <button @click="removeSmeshariki(index)">Del</button>
</li>
</ul>
</template>

<style>
</style>