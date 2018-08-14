<template>
    <header class="header">
        <span class="header-home">首页</span>
        <h3 class="header-title">电影</h3>
    </header>
    
</template>

<script>
export default {
    
}
</script>

<style lang="sass" scoped>
.header{
    height:1rem;
    backgorund-color:#e54847;
    line-height:1rem;
    position:fixed;
    top:0;
    left:0;
    wtdth:100%;
    color:#fff;
    &-home{
        margin-left:0.2rem;
    }
    &-title{
        top:50%;
        left：50%；
        transform:translate(-50%,-50%);
        position:absolute;
    }
},
</style>
