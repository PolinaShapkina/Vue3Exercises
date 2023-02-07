<script>
import Smeshariki from './components/User.vue'
export default {
data() {
    return {
    smeshariki: [
        {
        id: 1,
        name: 'Polina',
        salary: 25000,
        age: 18
        },
        {
        id: 2,
        name: 'Diana',
        salary: 20000,
        age: 19
        },
        {
        id: 3,
        name: 'David',
        salary: 30000,
        age: 19
        },
    ],
}
},
components: {
    Smeshariki
}
}

</script>

<template>
<Smeshariki v-for="smesharikis in smeshariki" :name="smesharikis.name" :salary="smesharikis.salary" :age="smesharikis.age" :key="smesharikis.id" />
</template>
<style>
</style>