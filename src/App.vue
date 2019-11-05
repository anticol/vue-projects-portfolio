<template>
    <div id="app">
        <Intro/>
        <Skills/>
        <Portfolio/>
    </div>
</template>

<script>
    import Intro from './components/Intro'
    import Skills from './components/Skills'
    import Portfolio from './components/Portfolio'
    import 'bootstrap/dist/css/bootstrap.css'
    import 'bootstrap-vue/dist/bootstrap-vue.css'
    import Vue from 'vue'
    import {BModal} from 'bootstrap-vue'
    import {VBModal} from 'bootstrap-vue'

    Vue.component('b-modal', BModal);
    Vue.directive('b-modal', VBModal);

    export default {
        name: 'app',
        components: {
            Intro,
            Skills,
            Portfolio
        }
    }
</script>

<style>
    body {
        background-color: #e8e8e8;
    }

    #app {
        font-family: Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 20px;
    }
</style>
