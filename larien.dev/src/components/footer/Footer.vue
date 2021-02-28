<template>
  <section id="footer">
    <div class="item" title='GitHub'>
      <a href="https://github.larien.dev" target="_blank"><GitHub/></a>
    </div>
    <div class="item" title='LinkedIn'>
      <a href="https://linkedin.larien.dev" target="_blank"><LinkedIn/></a>
    </div>
    <div class="item" title='Twitter'>
      <a href="https://twitter.larien.dev" target="_blank"><Twitter/></a>
    </div>
  </section> 
</template>

<script>
import GitHub from '../social/GitHub.vue';
import LinkedIn from '../social/LinkedIn.vue';
import Twitter from '../social/Twitter.vue';

export default {
  components: {
    GitHub,
    LinkedIn,
    Twitter,
  }
}
</script>

<style scoped>
#footer {
  margin-top: auto;
  height: 100px;
  display: flex;
  justify-content: center;
  margin-bottom: 20px;
}
.item {
  height: 80px;
  width: 80px;
  margin: 10px;
}
</style>