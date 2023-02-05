<script>
export default{
data(){
return{
    isSmeshariki: true,
}
},
methods: {
Smeshariki: function(){
this.isSmeshariki = false;
}
}
}
</script>

<template>
<button @click="Smeshariki">Smeshariki</button>
<p v-show="isSmeshariki">Nyusha</p>
</template>

<style >
</style>