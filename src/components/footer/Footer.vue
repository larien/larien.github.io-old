<template>
  <section id="footer">
    <div class="social">
    <div class="item" title='GitHub'>
      <a href="https://github.larien.dev" target="_blank"><GitHub/></a>
    </div>
    <div class="item" title='LinkedIn'>
      <a href="https://linkedin.larien.dev" target="_blank"><LinkedIn/></a>
    </div>
    <div class="item" title='Twitter'>
      <a href="https://twitter.larien.dev" target="_blank"><Twitter/></a>
    </div>
  </div>
    <div class="copyright">
      <p>© {{ currentYear }} Lauren Ferreira</p>
    </div>
  </section> 
</template>

<script>
import GitHub from '../social/GitHub.vue';
import LinkedIn from '../social/LinkedIn.vue';
import Twitter from '../social/Twitter.vue';

export default {
  data() {
    return {
      currentYear: new Date().getFullYear(),
    };
  },
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
}

.social {
  margin-top: auto;
  height: 70px;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.item {
  height: 70px;
  width: 70px;
  margin: 10px;
}

.copyright {
  color: rgb(190, 190, 190);
  font-size: 70%;
  cursor: default;
  position: absolute;
  padding: 10px;
}
</style>