<script>
export default{
data(){
return{
    smeshariki: ' ',
    conclave: ' ',
}
},
methods: {
list: function(){
}
}
}
</script>

<template>
<textarea class="text-field__input" v-model="smeshariki"></textarea>
<p>{{ smeshariki }}</p>
<br>
<button @click="Polina">Polina</button>
<ul>
<li v-for="Smeshariki in smeshariki">{{ Smeshariki }}</li>
</ul>
</template>

<style>
</style>