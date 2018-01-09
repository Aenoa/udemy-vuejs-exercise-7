<template>
    <div class="col-xs-12 col-sm-6">
        <ul class="list-group">
            <server v-for="index in 5" :key="index" :id="index"></server>
        </ul>
    </div>
</template>

<script>
import Server from './Server.vue'
export default {
    components: {
        'server': Server,
    }
}
</script>

<style>
</style>