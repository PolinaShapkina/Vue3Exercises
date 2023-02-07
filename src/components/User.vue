<script>
export default {
    emits: ['show', 'show1'],
    data() {
        return {
        }
    },
    methods: {
        aaa() {
            this.$emit('show');
        },
        bbb() {
            this.$emit('show1');
        },
    }
}
</script>

<template>
<button  @click="aaa">Smeshariki</button>
<button  @click="bbb">Student</button>
</template>