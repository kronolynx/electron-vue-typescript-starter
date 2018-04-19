<template lang="pug">
  div
    //- img#logo(src="~@src/renderer/assets/logo.png")
    h3.title Welcome 
    | This is the Home page {{`@src`}}
</template>

<script lang='ts'>
import Vue from "vue"
import Component from "vue-class-component"

@Component
export default class Home extends Vue {}
</script>




