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
    smesharikiName(name) {
    console.log(name);
    },
}
}

</script>

<template>
<Smeshariki @show="smesharikiName"/>
</template>
<style>
</style>