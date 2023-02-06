<script>
export default{
data(){
return{
    cssClasses: 'Smeshariki',
    obj: {
    done: true,
    selected: false,
}
}
}
}
</script>

<template>
<p :class="cssClasses">Smeshariki</p>
<p :class="obj">Krosh</p>
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
.selected{
    padding: 10px;
    margin: 10px;
    background: rgb(234, 129, 16);
    color: white;
    font-weight: bold;
    text-decoration: none;
    font-size: 20px;
}
.done {
    padding: 10px;
    margin: 10px;
    background: rgb(20, 247, 213);
    color: rgb(12, 51, 245);
    font-weight: bold;
    text-decoration: none;
    font-size: 20px;
}
</style>