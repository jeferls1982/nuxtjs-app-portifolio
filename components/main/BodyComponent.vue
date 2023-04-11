<template>
    <div>
        <div class="content">
         <MainLeftComponent class="left" />
         <MainCenterComponent class="center"/>
         <MainRigthComponent class="rigth" />

        </div>
    </div>
</template>

<script>

export default {
    setup () {
        

        return {}
    }
}
</script>

<style  scoped>
.content{
    display: flex;
    width: 100%;
    justify-content: space-between;
}
.center{
    background-color: pink;
    width: 60%;
}
.left,.rigth{
    background-color: blue;
    width: 20%;
    height: 85vh;
}
</style>