<template>
  <div id="app">
    <h1 class="flashing-text" style="text-align: center">Vernisity©</h1>
    <div style="width: 50%; margin: 0 auto; text-align: center">
      <img :src="'/media/b-funkychicken.gif'" alt="Retro GIF" />
      <h2>Clothing Brand in the making</h2>
    </div>
    <p class="flashing-paragraph" style="color: yellow; margin-left: 1%">
      Hi, I am currently working on making a unique clothing brand with features
      unseen before
    </p>
    <div style="text-align: center">
      <img :src="'/media/tweetysylvester84.gif'" alt="Retro GIF2" />
    </div>
  </div>
</template>

<script>
export default {
  name: "App", // Vue component name
};
</script>

<style>
.flashing-text {
  animation: flash 3s infinite;
}
@keyframes flash {
  0%,
  30%,
  60%,
  90% {
    color: red;
  }
  10%,
  40%,
  70%,
  100% {
    color: yellowgreen;
  }
  20%,
  50%,
  80% {
    color: rgb(255, 0, 255);
  }
}
.flashing-paragraph {
  animation: flash1 1s infinite;
}
@keyframes flash1 {
  0% {
    color: rgb(217, 255, 0);
  }
  50% {
    color: rgb(255, 0, 255);
  }
}
</style>
