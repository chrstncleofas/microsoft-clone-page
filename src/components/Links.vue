<template>
  <section class="links">
    <div class="links-inner">
      <ul>
        <li>
          <h3>What's New</h3>
        </li>
        <li><a href="#">Surface Pro X</a></li>
        <li><a href="#">Surface Laptop 3</a></li>
        <li><a href="#">Surface Pro 7</a></li>
        <li><a href="#">Windows 10 apps</a></li>
        <li><a href="#">Office apps</a></li>
      </ul>
      <ul>
        <li>
          <h3>Microsoft Store</h3>
        </li>
        <li><a href="#">Account Profile</a></li>
        <li><a href="#">Download Center</a></li>
        <li><a href="#">Microsoft Store support</a></li>
        <li><a href="#">Returns</a></li>
        <li><a href="#">Older tracking</a></li>
      </ul>
      <ul>
        <li>
          <h3>Education</h3>
        </li>
        <li><a href="#">Microsfot in education</a></li>
        <li><a href="#">Office for students</a></li>
        <li><a href="#">Office 365 for schools</a></li>
        <li><a href="#">Deals for studentss</a></li>
        <li><a href="#">Microsfot Azure</a></li>
      </ul>
      <ul>
        <li>
          <h3>Enterprise</h3>
        </li>
        <li><a href="#">Azure</a></li>
        <li><a href="#">AppSource</a></li>
        <li><a href="#">Automotive</a></li>
        <li><a href="#">Government</a></li>
        <li><a href="#">Healthcare</a></li>
      </ul>
      <ul>
        <li>
          <h3>Developer</h3>
        </li>
        <li><a href="#">Visual Studio</a></li>
        <li><a href="#">Windowszs Dev Center</a></li>
        <li><a href="#">Developer Network</a></li>
        <li><a href="#">TechNet</a></li>
        <li><a href="#">Microsoft Developer</a></li>
      </ul>
      <ul>
        <li>
          <h3>Company</h3>
        </li>
        <li><a href="#">Careers</a></li>
        <li><a href="#">About Microsoft</a></li>
        <li><a href="#">Company news</a></li>
        <li><a href="#">Privacy at Microsoft</a></li>
        <li><a href="#">Inverstors</a></li>
      </ul>
    </div>
  </section>
</template>

<script>
export default {
  name: "Links",
};
</script>

<style scoped>
.links {
  background: #f2f2f2;
  color: #616161;
  font-size: 12px;
  padding: 35px 0;
}

.links-inner {
  max-width: 1100px;
  margin: 0 auto;
  padding: 0 20px;
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  grid-gap: 10px;
  align-items: flex-start;
  justify-content: center;
}

.links li {
  line-height: 2.8;
}

@media (max-width: 700px) {
  .links .links-inner {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 500px) {
  .links .links-inner {
    grid-template-columns: 1fr;
  }

  .links .links-inner ul {
    margin-bottom: 20px;
  }
}
</style>