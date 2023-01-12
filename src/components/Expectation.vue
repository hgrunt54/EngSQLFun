<template>
    <section>
        <h4>The expected results should be similar to the following:</h4>
        <br />
        <table>
            <tr>
                <th class="tha">Login ID</th>
                <th>StaffGUID</th>
            </tr>
            <tr>
                <td>ADMIN</td>
                <td>420A97F0-7939-11D4-BD34-0050DAB66630</td>
            </tr>
            <tr>
                <td>MANAGER</td>
                <td>ABB122F7-F103-4D40-84FF-52443D2FDA7A</td>
            </tr>
            <tr>
                <td>PARTNER</td>
                <td>1F952853-5139-46B2-A536-CCC03D403C35</td>
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
        border: 2px solid black;
        border-collapse: collapse;
    }
    th {
        padding: .25rem 1rem .25rem 1rem;
        border: 2px solid black;
        background-color: lightgray;
        font-size: 1rem;
        text-align: center;
    }
    td {
        border: 1px dashed black;
        padding: .25rem 1rem .25rem 1rem;
        font-size: .75rem;
        text-align: left;
    }
</style>