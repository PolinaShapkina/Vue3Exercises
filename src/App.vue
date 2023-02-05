<script>
export default{
data(){
return{
    smeshariki: true,
}
},
methods: {
Smeshariki: function(){
this.smeshariki = false;
}
}
}
</script>

<template>
<button @click="Smeshariki">Smeshariki</button>
<div v-if="smeshariki">
<p>Pin</p>
<p>Nyusha</p>
<p>Krosh</p>
</div>
</template>

<style >
</style>