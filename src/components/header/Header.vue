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
  align-items: center;
}
img {
  height: 70px;
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

img {
  transition: 0.3s;
  border-radius: 10px;
}
img:hover {
  background-color: white;
  opacity: 1;
}
.ribbon {
  margin: 0;
  background: #1da1eb;
  color:white;
  padding:1em 10px;
  position: absolute;
  top:0;
  right:0;
  transform: translateX(30%) translateY(0%) rotate(45deg);
  transform-origin: top left;
}
</style>