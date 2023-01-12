<template>
    <section>
        <form>
            <label>Name: </label>
            <input type="text" /><br />
            <label>Email: </label>
            <input type="text" /><br /><br />
            <label>Script:</label><br />
            <textarea></textarea><br />
            <input type="submit" value="Submit!" />
        </form>
    </section>
</template>

<script setup lang="ts">

</script>

<style scoped>
    section {
        margin-left: 15rem;
    }
    textarea {
        margin-top: .5rem;
        border: 2px solid blue;
        width: 50vw;
        height: 25vh;
        resize: none;
    }
    input[type=text] {
        margin: .5rem;
    }
    input[type=submit] {
        margin-top: .5rem;
        padding: .5rem 1rem .5rem 1rem;
    }
</style>