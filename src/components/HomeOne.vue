<template>
  <section class="home-cards">
    <div>
      <img src="./img/card1.png" alt="" />
      <h3>New Surface Pro 7</h3>
      <p>
        See how Katie Sowers, Asst. Coach for the 49ers, uses Surface Pro 7 to
        put her plans into play.
      </p>
      <a href="#">Learn More <i class="fas fa-chevron-right"></i></a>
    </div>
    <div>
      <img src="./img/card2.png" alt="" />
      <h3>New Surface Laptop 3</h3>
      <p>
        Express yourself powerfully with a thin, light, and elegant design,
        faster performance, and up to 11.5 hours battery life.
      </p>
      <a href="#">Learn More <i class="fas fa-chevron-right"></i></a>
    </div>
    <div>
      <img src="./img/card3.png" alt="" />
      <h3>Save $150 + free controller</h3>
      <p>
        Buy an Xbox One X console and double your fun with a free select extra
        controller. Starting at $349.
      </p>
      <a href="#">Learn More <i class="fas fa-chevron-right"></i></a>
    </div>
    <div>
      <img src="./img/card4.png" alt="" />
      <h3>The new Microsoft Edge</h3>
      <p>
        Expect more. World class performance, with more privacy, more
        productivity, and more value.
      </p>
      <a href="#">Learn More <i class="fas fa-chevron-right"></i></a>
    </div>
  </section>
</template>

<script>
export default {
  name: "HomeOne",
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