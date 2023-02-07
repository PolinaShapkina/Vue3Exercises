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
removeStudents: function (id) {
    this.students = this.students.filter((student) => {
    return student.id !== id;
    })
}
}
}
</script>

<template>
<table>
<tr v-for="student in students" :key="student.id"> {{ student.name }} {{ student.surn }} {{ student.salary }} {{ student.age }} <button class="button" @click="removeStudents(students.id)">remove</button>
</tr>
</table>
</template>

<style>
</style>