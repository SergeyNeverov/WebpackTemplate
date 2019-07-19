<template>
  <section>
    <div class="container">
      <img src="/assets/img/no-image.jpg" :alt="message" />
      <p>{{ message }}</p>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      message: "simple component"
    };
  }
};
</script>

<style lang="scss" scoped>
.container {
  text-align: center;
}
img {
  max-width: 200px;
}
</style>
    
