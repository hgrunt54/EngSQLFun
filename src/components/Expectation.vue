<template>
    <section>
        <p>The expected results should be similar to the following:</p>
        <br />
        <table>
            <tr>
                <th class="tha">Login ID</th>
                <th>StaffGUID</th>
            </tr>
            <tr>
                <td>ADMIN</td>
                <td>420</td>
            </tr>
            <tr>
                <td>MANAGER</td>
                <td>456</td>
            </tr>
            <tr>
                <td>PARTNER</td>
                <td>123</td>
            </tr>
        </table>
    </section>
</template>

<script setup lang="ts">

</script>

<style scoped>
    section {
        margin-left: 15rem;
    }
    table {
        margin: 0 auto;
        border-style: solid;
        border-collapse: collapse;
    }
    th {
        padding: .25rem 1rem .25rem 1rem;
        border: solid;
        background-color: lightgray;
        font-size: 1rem;
        text-align: center;
    }
    td {
        border-style: dashed;
        padding: .25rem 1rem .25rem 1rem;
        font-size: .75rem;
        text-align: left;
    }
</style>