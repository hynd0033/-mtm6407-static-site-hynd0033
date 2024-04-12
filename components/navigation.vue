<template>

    <nav>
        <ul>
            <li v-for="navItem in navItems">
                <RouterLink :to="navItem.link">{{ navItem.title }}</RouterLink>
            </li>
        </ul>
    </nav>

</template>

<script setup>

const navItems = [

{
    title: 'Home',
    link: '/'
},
{
    title: 'Daredevil',
    link: '/dd'
},
{
    title: 'Breaking Bad',
    link: '/bb'
},
{
    title: 'Attack on Titan',
    link: '/aot'
},
{
    title: 'Better Call Saul',
    link: '/bcs'
},
{
    title: 'Fullmetal Alchemist: Brotherhood',
    link: '/fmab'
},

]

</script>

<style scoped>

ul {
    display: flex;
    justify-content: space-around;
}

@media screen and (max-width: 900px) {
    ul {
    display: flex;
    flex-direction: column;
    
}

}

</style>