<script>
import Add2 from "./Add.vue"
export default {
    components:{
        Add2
    }
}

</script>

<template>
    <div class="nav-bar">
        <div class="logo"></div>
        <div class="menu-bar"></div>
    </div>

    <Add2 />

</template>

<style scoped>

.nav-bar{
    background-color: #555;
}
.logo{
    width: 30px;
    height: 30px;
    background-color: antiquewhite;
}
</style>