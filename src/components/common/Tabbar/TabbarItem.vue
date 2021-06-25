<template>
    <div @click='itemClick'>
        <div v-if="active"><slot name='tabbar-img-active'></slot></div>
        <div v-if="!active"><slot name='tabbar-img'></slot></div>
        <div><slot name='tabbar-text'></slot></div>
    </div>
</template>

<script>
    export default {
        name: 'TabbarItem',
        data() {
            return {
                active: false
            }
        },
        methods: {
            itemClick() {
                console.log(1)
            }
        },
    }
</script>

<style>
    .tabbar img {
        height: 20px;
        width: 20px;
        background-color: #F6F6F6;
        vertical-align: top;
        margin: 4px 0 2px;
    }
</style>
