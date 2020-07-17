<template>
    <div class="aside-right">
        <h2>App Counter</h2>
        <p>Un sencillo contador usando Vue.js y Vuex más Holy Grail Layout</p>
        <p>Este es un ejemplo práctico para demostrar el uso de Vuex, store, mutations, actions, helpers como mapState y mapMutations en un app de Vue.js</p>
    </div>
</template>
<script>
export default {
    name: "AsideRight"
}
</script>
<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Montserrat&family=Roboto&display=swap');
.aside-right {
    border: 1px black solid;
    width: 25%;
    border-radius: 6px;
    display:flex;
    flex-direction: column;
}

h2 {
    text-align: center;
    font-family: 'Roboto', sans-serif;
}

p {
    padding: 1rem;
    font-family: 'Montserrat', sans-serif;
    line-height: 1.4rem;
    margin: 3rem 0;
}
</style>