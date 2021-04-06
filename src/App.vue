<template>
  <Slider />
</template>

<script>
  import Slider from "./components/Slider.vue";

  export default {
    name: 'App',
    components: {
      Slider
    }
  }
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
    background-color: #1e1e1e;
  }
    .div
    {
        background-color: #1e1e1e;
    }
body {
    margin: 0;
    font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans","Liberation Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.5;
    color: #212529;
    text-align: left;
    background-color: #1e1e1e !important;
}
.btn-success.disabled, .btn-success:disabled {
    color: #fff !important;
    height: 100px;
    width: 300px;
    background-color: #404040 !important;
    border-color: #404040 !important;
    border-radius: 25px;
    box-shadow: 0 3px 1px -2px rgb(0 0 0 / 20%), 0 2px 2px 0 rgb(0 0 0 / 14%), 0 1px 5px 0 rgb(0 0 0 / 12%);
}

.btn-success {
    color: #2c3e50 !important;
    height: 100px;
    width: 300px;
    background-color: #ffb9b9 !important;
    border-color: #404040 !important;
    border-radius: 25px  !important;
    box-shadow: 0 3px 1px -2px rgb(0 0 0 / 20%), 0 2px 2px 0 rgb(0 0 0 / 14%), 0 1px 5px 0 rgb(0 0 0 / 12%);
}

.btn-info.disabled, .btn-info:disabled {
    color: #fff !important;
    background-color: #ff4747 !important;
    border-color: #17a2b8  !important;
    border-radius: 25px  !important;
    box-shadow: 0 3px 1px -2px rgb(0 0 0 / 20%), 0 2px 2px 0 rgb(0 0 0 / 14%), 0 1px 5px 0 rgb(0 0 0 / 12%);
}
.btn-info {
    color: #2c3e50 !important;
    background-color: #ff4747 !important;
    border-color: #17a2b8  !important;
    border-radius: 25px  !important;
    box-shadow: 0 3px 1px -2px rgb(0 0 0 / 20%), 0 2px 2px 0 rgb(0 0 0 / 14%), 0 1px 5px 0 rgb(0 0 0 / 12%);
}
</style>