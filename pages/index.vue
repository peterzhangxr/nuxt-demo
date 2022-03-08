<template>
  <div>
    <img src="/nuxt.svg" alt="logo" width="100" />
    <h1>Hello World</h1>
    <img src="@/assets/dog.png" width="200" />
    <div class="box"></div>
  </div>
</template>
<style lang="less">
  .box {
    width: 200px;
    height: 200px;
    background: red url('~/assets/dog.svg') no-repeat center;
    background-size: 50% 50%;
  }
</style>
