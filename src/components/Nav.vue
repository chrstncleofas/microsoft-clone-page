<template>
  <nav class="main-nav">
    <img src="./img/logo.png" alt="Microsoft" class="logo" />

    <ul class="main-menu">
      <li><a href="#">Office</a></li>
      <li><a href="#">Windows</a></li>
      <li><a href="#">Surface</a></li>
      <li><a href="#">Xbox</a></li>
      <li><a href="#">Deals</a></li>
      <li><a href="#">Support</a></li>
    </ul>

    <ul class="right-menu">
      <li>
        <a href="#">
          <i class="fas fa-search"></i>
        </a>
      </li>
      <li>
        <a href="#">
          <i class="fas fa-shopping-cart"></i>
        </a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "Nav",
};
</script>

<style scoped>
/* Nav */
.main-nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 60px;
  padding: 20px 0;
  font-size: 13px;
}

.main-nav .logo {
  width: 110px;
}

.main-nav ul {
  display: flex;
}

.main-nav ul li {
  padding: 0 10px;
}

.main-nav ul li a {
  padding-bottom: 2px;
}

.main-nav ul li a:hover {
  border-bottom: 2px solid #262626;
}

.main-nav ul.main-menu {
  flex: 1;
  margin-left: 20px;
}

@media (max-width: 700px) {
  .menu-btn {
    display: block;
  }

  .menu-btn:hover {
    opacity: 0.5;
  }

  .main-nav ul.right-menu {
    margin-right: 50px;
  }

  .main-nav ul.main-menu {
    display: block;
    position: absolute;
    top: 0;
    left: 0;
    background: #f2f2f2;
    width: 50%;
    height: 100%;
    border-right: #ccc 1px solid;
    opacity: 0.9;
    padding: 30px;
    transform: translateX(-500px);
    transition: transform 0.5s ease-in-out;
  }

  .main-nav ul.main-menu li {
    padding: 10px;
    border-bottom: #ccc solid 1px;
    font-size: 14px;
  }

  .main-nav ul.main-menu li:last-child {
    border-bottom: 0;
  }

  .main-nav ul.main-menu.show {
    transform: translateX(-20px);
  }
}



</style>