<template>
    <div class="row">
        <servers></servers>
        <server-update></server-update>
    </div>
</template>

<script>
import Servers from './Servers.vue'
import ServerUpdate from './ServerUpdate.vue'
export default {
    components: {
        'servers': Servers,
        'server-update': ServerUpdate,
    }
}
</script>

<style>

</style>
