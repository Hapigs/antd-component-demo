<template>
  <div id="app">
    <div>
      <a-radio-group default-value="a" button-style="solid">
        <a-radio-button value="a">
          Hangzhou
        </a-radio-button>
        <a-radio-button value="b">
          Shanghai
        </a-radio-button>
        <a-radio-button value="c">
          Beijing
        </a-radio-button>
        <a-radio-button value="d">
          Chengdu
        </a-radio-button>
      </a-radio-group>
    </div>
    <div class="nav-bar"></div>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
  #app {
    padding: 20px;
    position: relative;
  }
  .nav-bar {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 30px;
    background-color: antiquewhite;
  }
</style>
