<template>
  <div id="app">
    <div class="container">
      <h1 class="header">Vernisity</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: "App", // Vue component name
};
</script>

<style>
body {
  background-color: black;
}
.container {
  height: 50em;
  position: relative;
}
.header {
  margin: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  margin-right: -50%;
  transform: translate(-50%, -50%);
  color: bisque;
  font-size: 80px;
  font-family: Georgia, "Times New Roman", Times, serif;
}
</style>
