<script>
import Smeshariki from './components/User.vue'
export default {
data() {
    return {
    name: 'Polina Shapkina',
    salary: '25000',
    age: '18',
    }
},
components: {
    Smeshariki
}
}
</script>

<template>
<Smeshariki :name="name" :salary="salary" :age="age"/>
</template>
<style>
</style>