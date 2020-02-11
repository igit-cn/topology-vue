<template>
  <div class="page-list">Test</div>
</template>

<script>
export default {
  data() {
    return {}
  },
  methods: {}
}
</script>

<style lang="scss">
.page-list {
  background-color: #e7e7e7;
  width: 100vw;
  height: 100%;
  padding: 0 0.3rem;
  overflow: auto;

  .nav {
    margin: 0.2rem 0.1rem 0.05rem 0.1rem;
  }

  & > div {
    max-width: 12rem;
    margin: auto;
  }
}
</style>
