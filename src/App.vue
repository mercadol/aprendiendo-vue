<template>
<div id="app">
    <HeaderComponent></HeaderComponent>
    <Header></Header>
    <slider-component></slider-component>
    <div class="center">
        <last-articles></last-articles>
        <sidebar></sidebar>
    </div>
    <div class="clearfix"></div>
    <footer-component></footer-component>
</div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
//import MiComponente from '@/components/MiComponente'
import HeaderComponent from './components/HeaderComponent.vue';
import SliderComponent from '@/components/SliderComponent';
import Sidebar from '@/components/Sidebar'
import LastArticles from '@/components/LastArticles'
import FooterComponent from '@/components/FooterComponent'

export default {
    name: 'App',
    components: {
        HeaderComponent,
        SliderComponent,
        Sidebar,
        LastArticles,
        FooterComponent
    }
}
</script>

<style>
/*
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
*/
@import './assets/css/styles.css'
</style>
