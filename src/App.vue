<script>
export default{
data(){
return{
    num: 0,
    res: 0,
sum: 0,
num1: 0, 
num2: 0,
}
},
methods: {
Smeshariki: function () {
    this.res = Math.sqrt(this.num);
},
smeshariki:function(){
    this.sum = this.num1 + this.num2;
}
}
}
</script>

<template>
<p>{{ res }}</p>
<input class="text-field__input" v-model="num">
<button @click="Smeshariki">квадратный корень</button>
<br>
<p>{{ sum }}</p>
<input class="text-field__input" v-model=num1>
<input class="text-field__input" v-model=num2>
<button @click="smeshariki">сумма</button>
<br>
</template>

<style>
</style>