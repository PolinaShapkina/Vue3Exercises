<script>
export default{
data(){
return{
    text: 'Krosh',
}
},
methods: {
change: function(){
    this.text = 'Pin';
},
change2: function(){
this.text = 'Nyusha'
}
}
}
</script>

<template>
<p>{{ text }}</p>
<button @click="change">Pin</button>
<button @click="change2">Nyusha</button>
</template>

<style >
</style>