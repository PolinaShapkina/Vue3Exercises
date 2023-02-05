<script>
export default{
data(){
return{
}
},
methods: {
show: function(str){
alert(str*str);
},
show1: function(str1){
    alert(str1*str1)
}
}
}
</script>

<template>
<button  @click="show(2)">btn1</button>
<button  @click="show1(3)">btn2</button>
</template>

<style >
</style>