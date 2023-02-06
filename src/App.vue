<script>
export default{
data(){
return{
    languages: '',
    languages1: false,
    languages2: false,
    languages3: false,
}
},
methods: {
aaa(){
    this.languages1 = true;
},
bbb() {
    this.languages2 = true;
},
vvv() {
    this.languages3 = true;
}
}
}
</script>

<template>
<div>
<p>На каком языке вы разговариваете?</p>
<input name="radio" type="radio" v-model="languages" value="Русский" @click="aaa">
<label for="">Русский</label>
<br>
<input name="radio" type="radio" v-model="languages" value="Английский" @click="bbb">
<label for="">Английский</label>
<br>
<input name="radio" type="radio" v-model="languages" value="Украинский" @click="vvv">
<label for="">Украинский</label>
</div>
<p v-if="visible">Здравствуйте</p>
<p v-else-if="visible1">Hello</p>
<p v-else-if="visible2">Привіт</p>
<p v-else=''> </p>

<p>ОТВЕТ: {{ languages }}</p>
<br>
</template>

<style>
</style>