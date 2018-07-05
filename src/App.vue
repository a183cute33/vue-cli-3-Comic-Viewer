<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
*{
  margin: 0;
  padding: 0;
  border: 0;
  font: inherit;
  vertical-align: baseline;
  box-sizing:border-box;
}
html {
  min-height: 100%;
}
body {
    position: relative;
    display: inline-block;
    width: 100%;
    min-height: 100%;
    color: ragb(90, 90, 90, 1.00);
    text-align: center;
    font-size: medium;
    font-family: Roboto, RobotoDraft, Helvetica, Arial, sans-serif, "微軟正黑體", "Microsoft JhengHei";
    background: rgba(242, 242, 242, 1.00);
  }
</style>
