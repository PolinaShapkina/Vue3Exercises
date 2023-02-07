<script>
export default {
    emits: ['show', 'show1'],
    data() {
        return {
        }
    },
    methods: {
        aaa() {
            this.$emit('show','Polina Shapkina');
        },
        bbb() {
            this.$emit('show1','Diana Kyzmenko','12345');
        },
    }
}
</script>

<template>
<button  @click="aaa">Name</button>
<button  @click="bbb">Salary</button>
</template>