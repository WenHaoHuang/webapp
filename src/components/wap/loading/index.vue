/**
* @author : wenhao.huang
* @date   : 2018/1/10
*/

<template>
    <transition name="fade">
        <article class="page-loading" v-if="status">
            <svg viewBox="25 25 50 50" class="circular"><circle cx="50" cy="50" r="20" fill="none" class="path"></circle></svg>
        </article>
    </transition>
</template>

<script>
    export default {
        name: "loading",
        data(){
            return {
                status: false
            }
        }
    }
</script>

<style lang="scss">
@import "./index";
</style>
