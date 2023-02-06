<script>
export default{
data(){
return{
    cssClasses: 'Smeshariki',
    visible: true,
    style: {
    hidden: true,
}
}
},
methods: {
setDone:function(){
this.style.hidden = false;
},
setTwo: function(){
this.style.hidden = true;
},
smeshariki: function () {
    this.visible = !this.visible;
}
}
}
</script>

<template>
<button @click="smeshariki">Smeshariki</button>
<p class="Smeshariki" v-if="visible">Smeshariki</p>
<p :class="style">Conclave</p>
<button @click="setDone">показывает</button>
<button @click="setTwo">прячет</button>
</template>

<style >
.Smeshariki {
    padding: 10px;
    margin: 10px;
    background: rgb(160, 204, 0);
    color: rgb(255, 255, 255);
    font-weight: bold;
    text-decoration: none;
    font-size: 20px;
}
p.hidden{
display: none;
}
</style>