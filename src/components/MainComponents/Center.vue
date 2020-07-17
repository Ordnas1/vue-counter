<template>
    <div class="main-center">
        <h1>Asesoría</h1>
        <p class="counter">{{ currentCount }}</p>
        <div class="btn-container">
            <button @click="decrement">-</button>
            <button @click="increment">+</button>
        </div>
    </div>
</template>
<script>
import { mapState } from 'vuex'
import { mapMutations } from 'vuex'

export default {
    name: 'Center',
    computed: mapState({
        currentCount: state => state.count
    }),
    methods: {
        ...mapMutations([
            'increment',
            'decrement'
        ])
    }
}
</script>
<style scoped lang="scss" >
@import url('https://fonts.googleapis.com/css2?family=Montserrat&family=Roboto&display=swap');
@import url('https://fonts.googleapis.com/css2?family=VT323&display=swap');

h1 {
    text-align: center;
    font-family: 'Roboto', sans-serif;    
}

.main-center {
    border: 2px #34495E solid;
    width: 45%;
    border-radius: 6px;
    display: flex;
    flex-direction: column;
    
}
.counter {
    text-align: center;
    font-family: 'VT323', monospace;
    font-size: 10rem;
}

.btn-container {
    display: flex;
    justify-content: center;

    & button{
        margin:0 0.3rem
    }
}
</style>