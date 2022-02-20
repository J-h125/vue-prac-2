<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <div @click="toAbout">这里是主页</div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
  },
  methods: {
    toAbout() {
      this.$router.push({ path: '/about' });
    },
  },
};
</script>
<style lang="scss" scoped>
.home{
  >div {
    border: 1px solid red;
  }
}
</style>
