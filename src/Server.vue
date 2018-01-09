<template>
    <li class="list-group-item">Server #{{id}}</li>
</template>

<script>
export default {
    props: {
        id: {
            type: String,
            default: 'Jack',
        }
    }
}
</script>

<style>
</style>