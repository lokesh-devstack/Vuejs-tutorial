<template>

    <div class="container">
        <Header title="Vue App" action="Get Started" color="red" bgcolor="black"/>
        

    </div>
        <div class="container">
        <Header title="Book App" action="Add books"/>
        

    </div>

</template>

<script>

import Header from './Header.vue'

export default {
    name: "App",
    components: {
        Header
    }
}

</script>

<style>
    #app {
        text-align: center;
        color: yellowgreen;
        margin-top: 60px;
    }

    .container {
        border: 1px solid steelblue;
        padding: 30px;
        max-width: 500px;
        margin: 20px auto;
    }

    button {
        padding: 10px 20px;
        font-size: 15px;
        background: seagreen;
        color: white;
        button-radius: 8px;
        border: none;
        cursor: pointer;
    }

</style>