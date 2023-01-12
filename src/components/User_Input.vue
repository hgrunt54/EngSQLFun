<template>
    <section>
        <form id="input-form" class="form" action="https://formsubmit.co/gary.bouck@wolterskluwer.com" method="POST">
            <input type="hidden" name="_subject" value="WK SQL Fun!">
            <input type="hidden" name="_next" value="https://transcendent-lollipop-48951b.netlify.app/">
            <label for="empName">Name: </label>
            <input type="text" id="empName" name="empName" placeholder="Your Name Here" required /><br />
            <label for="empEmail">Email: </label>
            <input type="text" id="empEmail" name="empEmail" placeholder="Email Address" required /><br /><br />
            <h3>Script:</h3>
            <textarea id="script" name="script" required></textarea><br />
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
        width: 15vw;
        margin: .5rem;
    }
    input[type=submit] {
        margin-top: 1rem;
        padding: .5rem 1rem .5rem 1rem;
    }
</style>