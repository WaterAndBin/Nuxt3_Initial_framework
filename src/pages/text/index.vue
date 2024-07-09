<template>
  <div class="flex flex-col items-center justify-center">
    <h2 class="bg-red-500">测试</h2>
    <h3>image的使用</h3>
    <nuxt-img src="/冰冰.jpg" class="h-100" />
    <h4>svg的使用</h4>
    <nuxt-icon name="list" class="h-10 w-10" @click="showList" />
  </div>
</template>

<script lang="ts" setup>
// const a = ref<number>(1);

const showList = (): void => {
  console.log('你好');
};
</script>
