<template>
  <section id="header">
    <div class="item logo">
      <a href="https://www.notion.so/larienmf/larien-dev-ecfa0060ecf7499891048570649be970"  target="_blank" class="logo"><img src='../../../public/logo.svg' title="I'm the Avatar and you gotta deal with it!"/></a>
    </div>
    <div class="social">
      <div class="item" title="Aprenda Go com Testes">
        <a href="https://go.larien.dev" target="_blank"><Go/></a>
      </div>
      <div class="item" title="Instagram">
        <a href="https://notion.larien.dev" target="_blank"><Instagram/></a>
      </div>
      <div class="item" title="Blog">
        <a href="https://blog.larien.dev" target="_blank"><Blog/></a>
      </div>
    </div>
    <div class="options">
      <div class="item"></div>
    </div>
  </section>
</template>

<script>

import Instagram from '../content/Instagram.vue';
import Blog from '../content/Blog.vue';
import Go from '../content/Go.vue';

export default {
  components: {
    Instagram,
    Blog,
    Go
  }

}
</script>

<style scoped>
#header {
  height: 100px;
  margin-bottom: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.social {
  display: flex;
  justify-content: center;
  align-items: center;
}
.item {
  height: 70px;
  width: 70px;
  margin: 10px;
  display: flex;
}
.logo {
  margin: 10px;
}

img {
  width: 70px;
  transition: 0.3s;
  border-radius: 10px;
}
img:hover {
  background-color: white;
  opacity: 1;
}
</style>