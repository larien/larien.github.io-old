<template>
  <section id="footer">
    <div class="item">
      <Email/>
    </div>
    <div class="item">
      <LinkedIn/>
    </div>
    <div class="item">
      <Twitter/>
    </div>
  </section> 
</template>

<script>
import Email from '../social/Email.vue';
import LinkedIn from '../social/LinkedIn.vue';
import Twitter from '../social/Twitter.vue';

export default {
  components: {
    Email,
    LinkedIn,
    Twitter
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