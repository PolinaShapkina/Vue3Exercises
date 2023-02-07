<script>
export default {
    data() {
        return {
            newName: ' ',
            newSurn: ' ',
        }
    },
    methods: {
        save(){
            this.$emit('add', this.newName, this.newSurn)
        }
    }
}
</script>

<template>
    <input class="text-field__input" v-model="newName">
    <br>
    <br>
    <input class="text-field__input" v-model="newSurn">
    <br>
    <button class="button" @click="save">сохранить</button>
</template>