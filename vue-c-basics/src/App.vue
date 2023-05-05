<script>
import Footer from './components/Footer.vue';
import NavBar from './components/NavBar.vue';
import Sum from './components/Sum.vue';
import Conditional from './components/Conditional.vue';
import Bucle from './components/Bucle.vue'
export default {
    name: 'App',
    data(){

    },
    components: {
        NavBar,
        Footer,
        Sum,
        Conditional,
        Bucle
    }
}
</script>

<template>
<NavBar></NavBar>
<Footer></Footer>
<Sum></Sum>
<Conditional></Conditional>
<Bucle></Bucle>
</template>

<style scoped>
</style>
