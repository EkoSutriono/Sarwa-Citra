<template>
  <div class="navmenu w-100">
      <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll" aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div id="navbarScroll" class="collapse navbar-collapse">
      <ul class="navbar-nav me-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">For You</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Discover</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Category
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Animation</a></li>
            <li><a class="dropdown-item" href="#">Illustration</a></li>
            <li><a class="dropdown-item" href="#">3D Assets</a></li>
            <li><a class="dropdown-item" href="#">.Etc</a></li>
          </ul>
        </li>
      </ul>
      <div class="container-fluid menu2 gap-4">
        <div class="input-group flex-nowrap">
            <img id="addon-wrapping" class="input-group-text search" src="../assets/icon/search.svg" alt="">
            <input type="text" class="form-control search" placeholder="Search Something" aria-describedby="addon-wrapping">
        </div>
        <img src="../assets/icon/default-profile.svg" alt="" width="30px">
        <img src="../assets/icon/notif.svg" alt="" width="27px">
      </div>
    </div>
  </div>
</nav>
  </div>
</template>

<script>
export default {
  name: 'NuxtNavMenu',
}
</script>

<style scoped>
* {
    background-color: white;
    z-index: 98;
}

a {
    color: black;
}

.menu1 {
    display: flex;
    justify-content: start;
}
.menu2 {
    display: flex;
    justify-content: end;
    margin-top: 5px;
}

.search {
    border-radius: 20px;
    border-width: 1px;
    border-color: rgb(140, 140, 140);
}
.nav-item {
    width: 100px;
}

.input-group {
    width: 30%;
}
.input-group-text {
    background-color: transparent;
    border-right: none;
}
.navmenu {
  box-shadow: 0 2px 7px 0 rgba(0, 0, 0, 0.1);
  height: 60px;
}
.but-item {
  margin-left: 4%;
}

</style>