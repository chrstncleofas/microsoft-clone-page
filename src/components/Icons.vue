<template>
  <section class="follow">
    <p>Follow Microsoft</p>
    <a href="https://facebook.com">
      <img src="https://i.ibb.co/LrVMXNR/social-fb.png" alt="Facebook" />
    </a>
    <a href="https://twitter.com">
      <img src="https://i.ibb.co/vJvbLwm/social-twitter.png" alt="Twitter" />
    </a>
    <a href="https://linkedin.com">
      <img src="https://i.ibb.co/b30HMhR/social-linkedin.png" alt="Linkedin" />
    </a>
  </section>
</template>

<script>
export default {
  name: "Icons",
};
</script>

<style scoped>

/* Follow */
.follow {
  display: flex;
  align-items: center;
  justify-content: flex-start;
  margin: 30px 0 30px;
}

.follow * {
  margin-right: 10px;
}

</style>