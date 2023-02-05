<script>
export default{
data(){
return{
    visible: true,
    visible1: false,
	hidden: true,
    hidden1: false,
}
},
}
</script>

<template>
<p v-if="visible">Krosh</p>
<p v-if="!visible1">Pin</p>
<p v-if="hidden">Olga</p>
<p v-if="!hidden1">Nyusha</p>
</template>

<style >
</style>