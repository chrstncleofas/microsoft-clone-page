<template>
  <section class="xbox">
    <div class="content">
      <h2>Xbox Game Pass Ultimate</h2>
      <p>
        Xbox Game Pass Ultimate Xbox Live Gold and over 100 high-quality console
        and PC games. Play together with friends and discover your next favorite
        game.
      </p>
      <a href="#" class="btn">
        Join Now <i class="fas fa-chevron-right"></i>
      </a>
    </div>
  </section>
</template>

<script>
export default {
    name: "Xbox"
}
</script>

<style scoped>

/* Xbox */
.xbox {
  width: 100%;
  height: 350px;
  background: url('./img/xbox.png') no-repeat center center/cover;
  margin-bottom: 20px;
}

.xbox .content {
  width: 40%;
  padding: 50px 0 0 30px;
}

.xbox p, .carbon p {
  margin: 10px 0 20px;
}

@media(max-width: 700px) {
  .xbox .content p {
    display: none;
  }

  .xbox .content h2 {
    margin-bottom: 20px;
  }
}

</style>