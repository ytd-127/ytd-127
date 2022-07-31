<template>
    
    <div class="dhfont" @click="itemClick">
        <slot name="item-text"></slot>
    </div>
    
</template>

<script>
export default {
    name:"NavTopItem",
    props:{
        path:String,
        activeColor:{
            sype:String,
            default:'red'
        }
    },
    methods: {
      itemClick() {
        this.$router.replace(this.path)
      }
    }

}
</script>

<style>

</style>