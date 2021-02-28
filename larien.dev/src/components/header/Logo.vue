<template>
  <div class="logo">
    <img :src="logo" />
</div>
</template>

<script>
export default {
    data(){
    return {
      logo: require('../../../public/logo.svg')
    }
  }
}
</script>

<style>
img {
    height: 80px;
    height: 80px;
}
</style>