<script>
export default {
    emits: ['show'],
    data() {
        return {
        }
    },
    methods: {
    }
}
</script>

<template>
<button @click="$emit('show', 'Polina Shapkina')">Name</button>
</template>