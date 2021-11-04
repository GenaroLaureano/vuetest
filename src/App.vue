<template>
    <div id="app">
        <img alt="Vue logo" src="./assets/logo.png">
        <div class="box">
            <p><strong>Basic Example</strong></p>
            <ToggleButton />
        </div>
    </div>
</template>

<script>
import ToggleButton from './components/ToggleButton.vue'

export default {
    name: 'App',

    components: {
        ToggleButton
    }
}
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}

.box {
    text-align:center;
    margin-bottom: 30px;
}
</style>
