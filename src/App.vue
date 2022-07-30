<template>
  <div class="docker">
    <div class="docker__item">首页</div>
    <div class="docker__item">购物车</div>
    <div class="docker__item">订单</div>
    <div class="docker__item">我的</div>
  </div>
</template>

<style lang="scss">
  .docker {
    display: flex;
    box-sizing: border-box;
    position: absolute;
    padding: 0 .18rem;
    left: 0;
    bottom: 0;
    width: 100%;
    height: .49rem;
    border-top: 1px solid #F1F1F1;
    background: green;
  }
  .docker__item {
    flex: 1;
    text-align: center;
  }
</style>
