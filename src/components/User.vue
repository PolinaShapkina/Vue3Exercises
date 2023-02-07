<script>
export default {
    props: ['name'],
    data() {
        return {
        }
    }
}
</script>

<template>
<ul>
    <li v-for="smeshariki in name">{{ smeshariki }}</li>
</ul>
</template>