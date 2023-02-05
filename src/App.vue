<script>
export default{
data(){
return{
    Smeshariki: ['Nyusha','Pin','Krosh']
}
},
methods: {
add: function(){
this.Smeshariki.push('Olga');
},
del: function(){
this.Smeshariki.shift();
},
del1: function () {
this.Smeshariki.pop();
},
splice: function(){
this.Smeshariki.splice(2, 1);
},
sort: function(){
this.Smeshariki.sort();
},
reverse: function () {
    this.Smeshariki.reverse();
},
}
}
</script>

<template>
<ul>
<li v-for="elem in Smeshariki">{{ elem }}</li>
</ul>
<button @click="add">1</button>
<br>
<button @click="del">2</button>
<br>
<button @click="del1">3</button>
<br>
<button @click="splice">4</button>
<br>
<button @click="sort">5</button>
<br>
<button @click="reverse">6</button>
</template>

<style >
</style>