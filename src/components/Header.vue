<template >
    <div>
        <nav>
            <ul>
                <li>Inicio</li>
                <li>Quienes Somos</li>
                <li>Contacto</li>
            </ul>
        </nav>
    </div>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Montserrat&family=Roboto&display=swap');
$f-title: 'Roboto', sans-serif;
$f-text: 'Montserrat', sans-serif;
    div {
        margin: 0.5rem 0;
    }


    nav {
        display: flex;
        justify-content: flex-end;
        border: 2px #41B883 solid;
        border-radius: 6px;
        
    }

    ul {
        display: flex;
        list-style-type: none;

    }

    li {
        margin: 0 1rem;
        font-family: $f-text
    }
</style>