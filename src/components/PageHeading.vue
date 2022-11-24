<template>
    <div className="heading">
        <h1>{{heading}}</h1>
    </div>
</template>

<script>
    export default {
        name: "PageHeading",
        data() {
            return {
                heading: "Bruno Costa"
            }
        }
    }
</script>

<style>
    .heading {
        font-family: 'roboto';
    }
</style>