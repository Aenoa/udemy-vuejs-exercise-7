<template>
    <div class="container">
        <header-element></header-element>
        <hr>
        <body-element></body-element>
        <hr>
        <footer-element></footer-element>
    </div>
</template>

<script>
import HeaderElement from './HeaderElement.vue'
import BodyElement from './BodyElement.vue'
import FooterElement from './FooterElement.vue'
export default {
    components: {
        'header-element': HeaderElement,
        'body-element': BodyElement,
        'footer-element': FooterElement,
    }
}
</script>

<style>

</style>
