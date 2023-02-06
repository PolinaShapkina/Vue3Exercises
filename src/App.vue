<script>
export default{
data(){
return{
    dayOfWeek: 'Понедельник',
    a: ['Понедельник', 'Вторник','Среда', 'Четверг', 'Пятница','Суббота', 'Воскресенье'], 
    day: '6',
    b: ['1', '2', '3', '4', '5', '6', '7', '8', '9', '10', '11', '12', '13', '14', '15', '16', '17', '18', '19', '20', '21', '22', '23', '24', '25', '26', '27', '28', '29', '30',' 31'],
    month: 'Февраль',
    v: ['Январь', 'Февраль','Март', 'Апрель', 'Май','Июнь', 'Июль', 'Август', 'Сентябрь','Октябрь', 'Ноябрь', 'Декабрь'],
    year: '2023',
    g: ['2023', '2022','2021', '2020', '2019','2018']
}
}
}
</script>

<template>
    <select v-model="dayOfWeek">
    <option v-for="a in a">{{ a }}</option>
    </select>
<br>
<select v-model="day">
<option v-for="b in b">{{ b }}</option>
</select>
<br>
<select v-model="month">
<option v-for="v in v">{{ v }}</option>
</select>
<br>
<select v-model="year">
<option v-for="g in g">{{ g }}</option>
</select>
</template>

<style>
</style>