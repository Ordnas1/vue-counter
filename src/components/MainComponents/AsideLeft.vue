<template>
    <div class="aside-left">
        <h2>Conceptos Utilizados</h2>
        <ul>
            <li>Vue.js</li>
            <li>Vuex</li>
            <li>Store</li>
            <li>Mutations</li>
            <li>Holy Grail Layout</li>
            <li>SASS</li>
            <li>Vue UI</li>
            
        </ul>
    </div>
</template>
<script>
export default {
    name: "AsideLeft"
}
</script>
<style scoped lang="scss">
    .aside-left {
    border: 1px black solid;
    width: 25%;
    border-radius: 6px;
}
h2 {
    text-align: center;
    font-family: 'Roboto', sans-serif;
}
ul {
    margin: 2rem 0;
}
li {
    font-family: 'Montserrat', sans-serif;
    padding: 1.4rem 0
}
</style>