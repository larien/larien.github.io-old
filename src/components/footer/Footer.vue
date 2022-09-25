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
    <p>© {{ new Date().getFullYear() }} Lauren Ferreira</p>
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
}

.item {
  height: 70px;
  width: 70px;
  margin: 10px;
}

p {
  position: absolute;
  bottom: 0px;
  margin: 10px;
  left: 0px;
  color: rgb(190, 190, 190);
  font-size: 70%;
  cursor: default;
}
</style>