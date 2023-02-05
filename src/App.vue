<script>
export default{
data(){
return{
    visible: true,
    visible2: true,
    visible3: true,
}
},
methods: {
Nyusha: function(){
    this.visible = !this.visible;
},
Pin: function () {
    this.visible2 = !this.visible2;
},
Krosh: function () {
    this.visible3 = !this.visible3;
}
}
}
</script>

<template>
<button @click="Nyusha">Nyusha</button>
<p v-if="visible">Nyusha</p>
<button @click="Pin">Pin</button>
<p v-if="visible2">Pin</p>
<button @click="Krosh">Krosh</button>
<p v-if="visible3">Krosh</p>
</template>

<style >
</style>