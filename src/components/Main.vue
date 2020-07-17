<template>
    <div class="main-content">
        <AsideRight/>
        <Center></Center>
        <AsideLeft/>
    </div>
</template>
<script>
import Center from './MainComponents/Center.vue'
import AsideRight from './MainComponents/AsideRight.vue'
import AsideLeft from './MainComponents/AsideLeft.vue'

export default {
    name: 'Main',
    components: {
        Center,
        AsideRight,
        AsideLeft
    }
}
</script>
<style scoped lang="scss" >
.main-content{
    display: flex;
    width: 100vw;
    justify-content: space-between;
    border-radius: 6px;
    height: 75vh;
}

</style>