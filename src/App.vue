<script>
export default{
data(){
return{
    isSmeshariki: [
    {href: '1.html',text: 'Polina Shapkina',},
    {href: '2.html',text: 'Polina Shapkina',},
    {href: '3.html',text: 'Polina Shapkina',},
    ],
    products: [
    {
        name: 'product1',
        price: 100,
        quantity: 5
    },
    {
        name: 'product2',
        price: 200,
        quantity: 4
    },
    {
        name: 'product3',
        price: 300,
        quantity: 3
    },
    ]
}
}
}
</script>

<template>
<ul class="styled">
    <li v-for="link in isSmeshariki"><a isSmeshariki="{{ link.isSmeshariki }}">{{ link.text }}</a></li>
</ul>
<br>
<br>
<table>
    <tr v-for="col in products">
    <td>{{ col.name }}</td>
    <td>{{ col.price }}</td>
    <td>{{ col.quantity }}</td>
    </tr>
</table>
</template>

<style >
</style>