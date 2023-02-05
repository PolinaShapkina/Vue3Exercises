<script>
export default{
data(){
return{
    Smeshariki: [
    {
        id: 1,
        name: 'Krosh',
    },
    {
        id: 2,
        name: 'Pin',
    },
    {
        id: 3,
        name: 'Nyusha',
    },
    ]
}
}
}
</script>

<template>
<p class= "styled" v-for="prod in Smeshariki" :key='Smeshariki.id'>{{ prod.name }}</p>
</template>

<style >
</style>