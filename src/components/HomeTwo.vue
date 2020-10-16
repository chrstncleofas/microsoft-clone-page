<template>
  <section class="home-cards">
    <div>
      <img src="https://i.ibb.co/zVqhWn2/card5.png" alt="" />
      <h3>Microsoft Teams</h3>
      <p>Unleash the power of your team.</p>
      <a href="#">Shop Now <i class="fas fa-chevron-right"></i></a>
    </div>
    <div>
      <img src="https://i.ibb.co/mGZcxcn/card6.jpg" alt="" />
      <h3>Unlock the power of learning</h3>
      <p>
        Get students future-ready with Windows 10 devices. Starting at $219.
      </p>
      <a href="#">Shop Now <i class="fas fa-chevron-right"></i></a>
    </div>
    <div>
      <img src="https://i.ibb.co/NpPvVHj/card7.png" alt="" />
      <h3>Windows 10 Enterprise</h3>
      <p>Download the free 90-day evaluation for IT professionals.</p>
      <a href="#">Download Now <i class="fas fa-chevron-right"></i></a>
    </div>
    <div>
      <img src="https://i.ibb.co/LkP4L5T/card8.png" alt="" />
      <h3>Explore Kubernetes</h3>
      <p>
        Learn how Kubernetes works and get started with cloud native app
        development today.
      </p>
      <a href="#">Get Started <i class="fas fa-chevron-right"></i></a>
    </div>
  </section>
</template>

<script>
export default {
  name: "HomeTwo",
};
</script>

<style scoped>
/* Home cards */
.home-cards {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-gap: 20px;
  margin-bottom: 40px;
}

.home-cards img {
  width: 100%;
  margin-bottom: 20px;
}

.home-cards h3 {
  margin-bottom: 5px;
}

.home-cards a {
  display: inline-block;
  padding-top: 10px;
  color: #0067b8;
  text-transform: uppercase;
  font-weight: bold;
}

.home-cards a:hover i {
  margin-left: 10px;
}

@media (max-width: 500px) {
  .home-cards {
    grid-template-columns: 1fr;
  }
}
</style>