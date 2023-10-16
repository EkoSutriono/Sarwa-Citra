<template>
    <div class="navbarS">
        <nav class="navbar bg-body-tertiary">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">
                    <img src="../assets/logo/sarwa-citra.png" alt="" class="logo">
                </a>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
  name: 'NuxtNavbar',
}
</script>

<style scoped>
* {
    background-color: white;
    z-index: 99;
}
.navbar {
    box-shadow: 0 2px 7px 0 rgba(0, 0, 0, 0.1);
    height: 70px;
}
.logo {
    height: 50px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

</style>