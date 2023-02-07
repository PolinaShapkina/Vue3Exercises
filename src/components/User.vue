<script>
export default {
    props: ['name', 'salary', 'age'],
    data() {
        return {
        }
    }
}
</script>

<template>
<p class="smeshariki">{{ name }} 
<br>
{{ salary }} 
<br>
{{ age }}</p>
</template>