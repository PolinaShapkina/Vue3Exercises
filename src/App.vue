<script>
export default{
data(){
return{
    languages: [],
}
}
}
</script>

<template>
<div>
<input type="checkbox" v-model="languages" value="Английский">
<label>Английский</label>
<br>
<input type="checkbox" v-model="languages" value="Русский">
<label>Русский</label>
<br>
<input type="checkbox" v-model="languages" value="Испанский">
<label>Испанский</label>
<ol>
<li v-for="elem in languages">{{ elem }}</li>
</ol>
</div>
<br>
</template>

<style>
</style>