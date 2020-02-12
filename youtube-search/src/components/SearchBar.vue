<template>
    <div>
        <input @input="onInput" />
    </div>
</template>

<script>
    export default {
        name: "SearchBar",
        methods: {
            onInput: function (event) {
                this.$emit('termChange', event.target.value);
            }
        }
    }
</script>

<style scoped>
    div {
        text-align: center;
        margin: 3rem;
    }
    input {
        width: 75%;
    }
</style>