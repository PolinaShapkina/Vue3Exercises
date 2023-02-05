<script>
export default{
data(){
return{
    isSmeshariki: [1, 2, 3],
}
}
}
</script>

<template>
<div v-for="elem in isSmeshariki">
<p>{{ elem }}</p>
<p class="divider"> </p>
</div>
<br>
<ul v-for="elem in isSmeshariki">
    <li>{{ elem }}</li>
    <li class="divider"> </li>
</ul>
</template>

<style >
</style>