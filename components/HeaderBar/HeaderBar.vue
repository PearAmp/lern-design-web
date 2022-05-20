<template>
    <nav>
      <div class="container">
        <input id="nav-toggle" type="checkbox" />
        <div class="logo">
          <!-- <img src="" alt="" class="imgicon" /> -->
          <strong>NEWS .</strong>
        </div>
        <ul class="links">
          <li class="content-link"><NuxtLink to="/">หน้าแรก</NuxtLink></li>
          <li class="content-link">
            <NuxtLink to="/about">เกี่ยวกับเรา</NuxtLink>
          </li>
          <li class="content-link"><NuxtLink to="/">ผลงาน</NuxtLink></li>
          <li class="content-link"> <NuxtLink to="/service">บริการ</NuxtLink></li>
          <li class="content-link"><NuxtLink to="/">ช่องทางติดต่อ</NuxtLink></li>
        </ul>
        <div>
          <div class="burger-icon">
            <ul>
              <label for="nav-toggle" class="icon-burger">
                <div class="line"></div>
                <div class="line"></div>
                <div class="line"></div>
              </label>
            </ul>
          </div>
        </div>
      </div>
    </nav>
</template>

<script>
export default {
  name: 'HeaderBar',
}
</script>

<style scoped>
.container {
  max-width: 100%;
  position: inherit;
  z-index: 10;
  left: 0;
  right: 0;
  top: 0;
  font-family: 'Monserrat', sans-serif;
  padding: 0.5%;
  height: 100px;
  background-color: #fff;
  border-bottom: 1px solid red;

}

.imgicon {
  width: 30px;
  height: 30px;
}

nav .logo {
  float: left;
  width: 40%;
  height: 100%;
  display: flex;
  align-items: center;
  font-size: 24px;
  color: #000;
}
nav .links {
  margin: 0;
  width: 60%;
  height: 100%;
  display: flex;
  justify-content: space-around;
  padding-top: 30px;
}

nav .links li {
  list-style: none;

}
nav .links a {
  display: block;
  padding: 1em;
  font-size: 16px;
  font-weight: bold;
  text-decoration: none;
  color: #000;

}
.content-link {
  padding-top: 15px;
}
.burger-icon {
  display: none;
}
#nav-toggle {
  top: -100px;
  display: none;
}
.nav .icon-burger {
  display: none;
  top: 50%;
}
nav .icon-burger .line {
  width: 30px;
  height: 5px;
  background-color: #000;
  margin: 5px;
  border-radius: 3px;
  transition: all 0.3s ease-in-out;
}
@media screen and (max-width: 576px) {
  nav .logo {
    width: 75%;
    justify-content: center;
    padding-top: 10px;
    margin-left: 40px;
  }

  .imgicon {
    width: 40px;
    height: 40px;
  }

  .burger-icon {
    display: block;
    position: absolute;
    top: 2rem;
    right: 10px;
  }
  nav .links {
    float: none;
    position: fixed;
    z-index: 9;
    left: 0;
    right: 0;
    bottom: 100%;
    width: auto;
    height: 89%;
    flex-direction: column;
    justify-content: space-evenly;
    color: #fff;
    background-color: #fff;
    overflow: hidden;
    transition: all 0.5s ease-in-out;
  }
  nav .links a {
    font-size: 20px;
  }
  nav :checked ~ .links {
    bottom: 0;
  }
  nav .icon-burger {
    display: block;
  }
  nav :checked ~ .icon-burger .line:nth-child(1) {
    transform: translate(10px) rotate(225deg);
  }
  nav :checked ~ .icon-burger .line:nth-child(3) {
    transform: translate(10px) rotate(-225deg);
  }
  nav :checked ~ .icon-burger .line:nth-child(2) {
    opacity: 0;
  }
}
</style>
