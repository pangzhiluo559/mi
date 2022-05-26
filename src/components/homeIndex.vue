<template>
    <div class="home w-full">
        <div class="h-full bg-gray-500 w-1/4 bg-opacity-20">
            <div class="h-10"></div>
            <div v-for="item in name" :key="item" class="w-full h-10 flex text-white font-bold hover:bg-orange-500">
                <div class="w-full h-full py-1.5 text-left ml-8">{{item}}</div>
                <img class="h-6 my-1 mr-8 " src="../assets/right.svg" alt="">
            </div>
        </div>
    </div>
</template>

<script setup>
const name = ['手机','电视','笔记本 平板','出行 穿戴','耳机 音箱','家电','智能 路由器','电源 配件','健康 儿童','生活 箱包']
</script>

<style scoped>
.home{
    background-image: url('../assets/1.png');
    background-size: cover;
    height: 500px;
}
</style>