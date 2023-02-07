<script>
import Smeshariki from './components/User.vue'
export default {
data() {
    return {
    
    }
},
components: {
    Smeshariki
},
methods: {
    aaa(name) {
    console.log(name);
    },
    bbb(name, salary){
console.log(name, salary);
    }
}
}

</script>

<template>
<Smeshariki @show="aaa" @show1="bbb"/>
</template>
<style>
</style>