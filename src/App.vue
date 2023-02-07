<script>
export default{
data(){
return{
    students: [
    {
        id: 1,
        name: 'Polina',
        surn: 'Shapkina',
        salary: 100,
				age: 30,
    },
    {
        id: 2,
        name: 'Diana',
        surn: 'Kyzmenko',
        salary: 200,
				age: 40,
    },
    {
        id: 3,
        name: 'David',
        surn: 'Avagyan',
        salary: 300,
				age: 50,
    },
    ],
}
},
methods: {
edit(student) {
    student.isEdit = true;
},
save(student) {
    student.isEdit = false;
},
}
}
</script>

<template>
<table>
<tr v-for="student in students" :key="student.id"> 
<template v-if="!student.isEdit">
{{ student.name }} {{ student.surn }} {{ student.salary }} {{ student.age }}<button class="button" @click="edit(student)">изменить</button>
</template>
<template v-else>
<input v-model="student.name">
<input v-model="student.surn">
<input v-model="student.salary">
<input v-model="student.age"><button class="button" @click="save(student)">сохранить</button>
</template>
</tr>
</table>
</template>

<style scoped>
</style>