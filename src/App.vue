<script>
export default{
data(){
return{
    aaa: 'Москва',
}
}
}
</script>

<template>
<p>В каком городе вы живете?</p>
    <select v-model="aaa">
    <option>Алушта</option>
    <option>Москва</option>
    <option>Санкт-Питербург</option>
    </select>
    <p>{{ aaa }}</p>
</template>

<style>
</style>