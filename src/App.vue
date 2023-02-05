<script>
export default{
data(){
return{
    cost: '70',
    amount: '15',
}
},
computed: {
price: function(){
    return this.cost *  this.amount;
}
},
methods: {
change: function(){
this.cost = '30'
}
}
}
</script>

<template>
<p>{{ cost }}</p>
<p>{{ amount }}</p>
<p>{{ price }}</p>
<button @click="change">cost</button>
</template>

<style >
</style>