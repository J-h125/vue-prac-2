<template>
  <div class="about">
    <h1>This is an about page</h1>
    <button @click="comeBack">返回主页</button>
  </div>
</template>
<script>
export default {
  name: 'about',
  components: {},
  data() {
    return {};
  },
  methods: {
    comeBack() {
      this.$router.push({ path: '/' });
    },
  },
};
</script>
