<template>
  <header class="showcase">
    <h2>Surface Deals</h2>
    <p>Select Surfaces are on sale now - save while supplies last</p>
    <a href="#" class="btn"> Shop Now <i class="fas fa-chevron-right"></i> </a>
  </header>
</template>

<script>
export default {
  name: "Showcase",
};
</script>

<style scoped>
.showcase {
  width: 100%;
  height: 400px;
  background: url("./img/slide1.png") no-repeat center
    center/cover;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  justify-content: flex-end;
  padding-bottom: 50px;
  margin-bottom: 20px;
}

.showcase h2,
.showcase p {
  margin-bottom: 10px;
}

.showcase .btn {
  margin-top: 20px;
}
</style>