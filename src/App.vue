<script>
export default{
data(){
return{
    isSmeshariki: ['x', 'y', 'z'],
}
}
}
</script>

<template>
<ul v-for="(elem, key) in isSmeshariki"> {{ key }} {{ elem }}</ul>
</template>

<style >
</style>