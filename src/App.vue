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
<a class="inline-link-1" href="https://losyash-library.fandom.com/ru/wiki/%D0%A1%D0%BC%D0%B5%D1%88%D0%B0%D1%80%D0%B8%D0%BA%D0%B8" onclick="event.preventDefault()">Krosh</a>
<br>
<br>
<button @click.once="show">Krosh</button>
</template>

<style >
</style>