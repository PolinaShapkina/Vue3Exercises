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
    Smeshariki() {
    alert('Pin, Nyusha, Krosh');
    },
    Student(){
    alert('David, Diana, Polina')
    }
}
}

</script>

<template>
<Smeshariki @show="Smeshariki" @show1="Student" />
</template>
<style>
</style>