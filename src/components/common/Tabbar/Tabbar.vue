<template name="tabbar">
    <div class='tabbar'>
        <slot></slot>
    </div>
</template>

<script>
    export default {
        name: 'Tabbar',
        components: {
            
        }
    }
</script>

<style>
    .tabbar {
        display: flex;
        text-align: center;
        background-color: #F6F6F6;
        height: 49px;
        width: 100%;
        position: fixed;
        bottom: 0;
        left: 0;
        box-shadow: 0 2px 4px rgba(00, 00, 00, .2)
    }
    .tabbar div {
        flex-grow: 1;
        font-size: 14px;
    }
    
</style>