<script>
import Smeshariki from './components/User.vue'
import UserForm from './components/UserForm.vue'


export default {
data() {
    return {
    smeshariki: [
        {
        id: 1,
        name: 'Pin',
        surn: 'Smeshariki'
        },
        {
        id: 2,
        name: 'Krosh',
        surn: 'Smeshariki'
        },
        {
        id: 3,
        name: 'Nyusha',
        surn: 'Smeshariki'
        },
    ],
    }
},
components: {
    Smeshariki, UserForm
},
methods: {
    add(name, surn){
    let id = this.smeshariki.length + 1;
    this.smeshariki.push({
        id, name, surn
    });
    }
}
}
</script>

<template>
<UserForm @add="add"/>
</template>

<style>
</style>