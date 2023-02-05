<script>
export default{
data(){

},
methods: {
show: function(){
    alert(new Date().toLocaleDateString());
}
}
}
</script>

<template>
<button  v-on:mouseover="show">наведение</button>
<button  @click="show">нажатие</button>
</template>

<style >
</style>