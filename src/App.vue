<script>
export default{
data(){
return{
    isSmeshariki: [1, -2, 3, -4, 5],
}
}
}
</script>

<template>
<ul>
    <template v-for="elem in isSmeshariki">
    <li v-if="elem > 0 ">{{ elem }}</li>
    </template>
</ul>
</template>

<style >
</style>