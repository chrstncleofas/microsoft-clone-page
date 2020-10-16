<template>
  <section class="carbon dark">
    <div class="content">
      <h2>Commiting To Carbon Negative</h2>
      <p>
        Microsoft will be carbon negative by 2030 and by 2050 we will remove all
        carbon the company has emitted since it was founded in 1975
      </p>
      <a href="#" class="btn">
        Learn More <i class="fas fa-chevron-right"></i>
      </a>
    </div>
  </section>
</template>

<script>
export default {
  name: "Carbon",
};
</script>

<style scoped>

.carbon {
  width: 100%;
  height: 350px;
  background: url('./img/carbon.jpg') no-repeat center center/cover;
}

.carbon .content {
  width: 55%;
  padding: 100px 0 0 50px;
}

.carbon .content p{
    margin-bottom: 20px;
}

@media(max-width: 700px) {
  .carbon .content {
    width: 85%;
  }
  .carbon p{
      margin-bottom: 20px;
  }
}

</style>