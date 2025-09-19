<template>

    <header>
    <h1 :style="{ color: color }">{{title}}</h1>
    <button @click="handleClick()" :style="{ background: bgcolor }">{{action}}</button>

    </header>

</template>

<script>
export default {
    name: "header",
    props: {
        title: String,
        action: String,
        color: String,
        bgcolor: String
    },

    methods: {
        handleClick() {
            alert('You clicked the button!')
        }
    }
}
</script>

<style>

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