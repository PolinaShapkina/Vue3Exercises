<script>
export default {
    props: {
        name: String, 
        salary: Number, 
        age: Number
    }
}
</script>

<template>
<p>{{ name }} 
<br>
{{ salary }} 
<br>
{{ age }}</p>
</template>