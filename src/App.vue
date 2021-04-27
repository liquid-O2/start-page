<template>
  <div class="box">
    <i class="fas fa-code"> <span> | sudo start</span></i>

    <a href="https://github.com/liquid-O2">Github</a>
    <a href="https://www.udemy.com/">Udemy</a>
    <a href="https://vuesax.com/docs/theme/#default-colors">Vuesax</a>
    <a href="https://v3.vuejs.org/guide/introduction.html">Vue</a>
    <a
      href="https://fontawesome.com/icons?d=gallery&p=2
"
      >FontAwesome</a
    >
    <a href="https://undraw.co/illustrations">Undraw</a>
    <a href="https://www.youtube.com/">Youtube</a>
    <a href="https://docs.google.com/document/u/0/">Docs</a>
    <i class="fas fa-terminal">
      <span> // continue your coding journey </span></i
    >
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Space+Mono&display=swap");
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: "Space Mono", monospace;
}
body {
  background-color: #2e3440;
  color: #e5e9f0;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
.box {
  background: #3b4252;
  border-radius: 0.75rem;
  width: fit-content;
  height: fit-content;
  display: flex;
  justify-content: space-between;
  flex-direction: column;
  padding: 2rem;
  flex: 0 1 30rem;
}
a {
  text-decoration: none;
  color: #e5e9f0;
  padding: 0.4rem 0rem;
}
i {
  padding: 1rem 0rem;
  font-size: 1.2rem;
  color: #8fbcbb;
}
i > span {
  font-family: "Space Mono", monospace;
}
</style>
