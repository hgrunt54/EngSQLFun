<template>
    <section>
        <form id="input-form" class="form" action="https://formsubmit.co/3fb13f7c8487de7f4a7b25ac78add79b" method="POST">
            <input type="hidden" name="_subject" value="WK SQL Fun!">
            <input type="hidden" name="_next" value="https://transcendent-lollipop-48951b.netlify.app/">
            <div class="form-floating mb-3">
                <input type="text" class="form-control" id="empName" name="Name" placeholder="Your Name Here" required />
                <label for="empName">Name</label>
            </div>
            <div class="form-floating mb-3">
                <input type="text" class="form-control" id="empEmail" name="Email" placeholder="Email Address" required />
                <label  for="empEmail">Email </label>
            </div>
            <h3>Script:</h3>
            <div class="form-floating mb-3">
                <textarea class="form-control fc2" id="script" name="script" placeholder="Enter your SQL Code here!" style="height: 25vh;" required></textarea>
                <label for="script">Enter Code</label>
            </div>
            
            <input class="btn btn-primary borderless" type="submit" value="Submit!" />
        </form>
    </section>
</template>

<script setup lang="ts">

</script>

<style scoped>
    section {
        margin-left: 15rem;
    }
    input {
        border: 2px solid blue;
    }
    textarea {
        border: 2px solid blue;
        resize: none;
    }
    .form-floating {
        margin: auto;
        width: 25%;
    }
    .borderless {
        border: none;
    }

</style>