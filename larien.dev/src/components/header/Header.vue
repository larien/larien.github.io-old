<template>
  <section id="header">
    <div class="item">
      <a class="logo"><img src='../../../public/logo.svg' title='I´m the Avatar and you gotta deal with it!'/></a>
    </div>
    <div class="social">
      <div class="item">
        <Notion/>
      </div>
      <div class="item">
        <Blog/>
      </div>
      <div class="item">
        <GitHub/>
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
import GitHub from '../content/GitHub.vue';

export default {
  components: {
    Notion,
    Blog,
    GitHub
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
  /* background-color: #555; */
}
</style>