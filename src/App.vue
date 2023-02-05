<script>
export default{
data(){
return{
    isSmeshariki: [1, 2, 3, 4, 5],
}
}
}
</script>

<template>
<div v-for="elem in isSmeshariki">{{ elem }}</div>
<br>
<div v-for="elem in isSmeshariki">{{ elem*elem }}</div>
<br>
<ul v-for="elem in isSmeshariki">{{ elem }}</ul>
</template>

<style >
</style>