<script>
export default{
data(){
return{
    cssClasses: 'Smeshariki',
}
}
}
</script>

<template>
<p :class="cssClasses">Smeshariki</p>
</template>

<style >
.Smeshariki {
    padding: 10px;
    margin: 10px;
    background: rgb(160, 204, 0);
    color: rgb(255, 255, 255);
    font-weight: bold;
    text-decoration: none;
    font-size: 20px;
}
</style>