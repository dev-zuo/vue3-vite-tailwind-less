<template>
    <div class="main">
        unocss 测试
        <div class="main-span">测试样式</div>
        <h1 class="text-3xl font-bold underline">
            Hello world!
        </h1>
        <button class="btn-primary">测试</button>
    </div>
</template>

<script lang="ts" setup>

</script>

<style lang="less">
.main-span {
    color: red;
    @apply bg-red-500 border-dashed border-spacing-3 text-white;
}

</style>

<style>
.btn-primary {
    @apply py-2 px-4 bg-blue-500 text-white font-semibold rounded-lg shadow-md hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-400 focus:ring-opacity-75;
}
</style>