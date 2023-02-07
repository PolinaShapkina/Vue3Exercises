<script>
import Smeshariki from './components/User.vue'


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
        name: 'Nyusha',
        surn: 'Smeshariki'
        },
        {
        id: 3,
        name: 'Krosh',
        surn: 'Smeshariki'
        },
    ],
    }
},
components: {
    Smeshariki
},
methods: {
    remove(id) {
    this.smeshariki = this.smeshariki.filter((smesharikis) => {
        return smesharikis.id !== id;
    })
    }
}
}
</script>

<template>
<Smeshariki v-for   ="smesharikis in smeshariki"
		:id     ="smesharikis.id"
		:name   ="smesharikis.name"
		:surn   ="smesharikis.surn"
		@remove ="remove"
		:key    ="smesharikis.id"/>
</template>
<style>
</style>