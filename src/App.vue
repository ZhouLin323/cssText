<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <HelloWorld>
      <p slot="hello">
        1234567
        <span slot="hello">qqqqqqq</span>
      </p>
    </HelloWorld>
    <Alert>
      <div class="name">还改不改湖北还改不改湖北还改不改湖北</div>
    </Alert>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import Alert from "./components/alert";
export default {
  name: "App",
  components: {
    HelloWorld,
    Alert
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.name {
  /* width: 100px; */
  /* height: 100px; */
}
</style>
