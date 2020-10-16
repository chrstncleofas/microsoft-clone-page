<template>
  <footer class="footer">
    <div class="footer-inner">
      <div><i class="fas fa-globe fa-2x"></i>English (United States)</div>
      <ul>
        <li><a href="#">Sitemap</a></li>
        <li><a href="#">Contact Microsoft</a></li>
        <li><a href="#">Privacy & cookies</a></li>
        <li><a href="#">Terms of use</a></li>
        <li><a href="#">Trademarks</a></li>
        <li><a href="#">Safety & eco</a></li>
        <li><a href="#">About our ads</a></li>
        <li><a href="#">&copy; Microsoft 2020</a></li>
      </ul>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.footer {
  background: #f2f2f2;
  color: #616161;
  font-size: 12px;
  padding: 20px 0;
}

.footer-inner {
  max-width: 1100px;
  margin: 0 auto;
  padding: 0 20px 0 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.footer div {
  margin-bottom: 20px;
  display: flex;
  align-items: center;
}

.footer div i {
  margin-right: 10px;
}

.footer ul {
  display: flex;
  flex-wrap: wrap;
  padding: 10px;
}

.footer li {
  margin-right: 30px;
  margin-bottom: 20px;
}

@media (max-width: 500px) {
  .footer div i {
    margin-right: 10px;
  }
  .footer div {
    text-align: center;
    padding-right: 40px;
  }
}
</style>