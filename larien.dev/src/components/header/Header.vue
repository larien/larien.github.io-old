<template>
  <section id="header">
    <div class="item">
      <a class="logo"><img src='../../../public/logo.svg' title="I'm the Avatar and you gotta deal with it!"/></a>
    </div>
    <div class="social">
      <div class="item" title="Aprenda Go com Testes">
        <a href="https://go.larien.dev" target="_blank"><Go/></a>
      </div>
      <div class="item" title="Notion">
        <a href="https://notion.larien.dev" target="_blank"><Notion/></a>
      </div>
      <div class="item" title="Blog">
        <a href="https://blog.larien.dev" target="_blank"><Blog/></a>
      </div>
    </div>
    <div class="options">
      <div class="item"></div>
      <div class="item"></div>
    </div>
  </section>
</template>

<script>

import Notion from '../content/Notion.vue';
import Blog from '../content/Blog.vue';
import Go from '../content/Go.vue';

export default {
  components: {
    Notion,
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
}
.social {
  display: flex;
  justify-content: center;
}
.item {
  height: 80px;
  width: 80px;
  margin: 10px;
}
img {
  transition: 0.3s;
  border-radius: 10px;
}
img:hover {
  background-color: white;
  opacity: 1;
}
</style>