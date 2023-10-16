<template>
  <div class="container text-center">
    <div class="row row-con">
      <div class="col contents">
        <div class="card" style="width: 18rem">
          <img
            src="../assets/image/cloud-boy.png"
            class="card-img-top foto"
            alt="..."
          />
          <div class="card-body">
            <div class="row"> 
                <div class="col-2">
                    <img class="profile-img" src="../assets/profile/eko.jpg" alt="">
                </div>
                <div class="col">
                    <h5 class="card-title">Cloud Boy</h5>
                    <p class="card-text">
                        Eko Soetriono
                    </p>
                </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col contents">
        <div class="card" style="width: 18rem">
          <img
            src="../assets/image/flower.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <div class="row"> 
                <div class="col-2">
                    <img class="profile-img" src="../assets/profile/eko.jpg" alt="">
                </div>
                <div class="col">
                    <h5 class="card-title">Flower</h5>
                    <p class="card-text">
                        Eko Soetriono
                    </p>
                </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col contents">
        <div class="card" style="width: 18rem">
          <img src="../assets/image/leaf.jpg" class="card-img-top" alt="..." />
          <div class="card-body">
            <div class="row"> 
                <div class="col-2">
                    <img class="profile-img" src="../assets/profile/eko.jpg" alt="">
                </div>
                <div class="col">
                    <h5 class="card-title">Leaf</h5>
                    <p class="card-text">
                        Eko Soetriono
                    </p>
                </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row row-con">
      <div class="col contents">
        <div class="card" style="width: 18rem">
          <img
            src="../assets/image/cloud-boy.png"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <div class="row"> 
                <div class="col-2">
                    <img class="profile-img" src="../assets/profile/eko.jpg" alt="">
                </div>
                <div class="col">
                    <h5 class="card-title">Cloud Boy</h5>
                    <p class="card-text">
                        Eko Soetriono
                    </p>
                </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col contents">
        <div class="card" style="width: 18rem">
          <img
            src="../assets/image/flower.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <div class="row"> 
                <div class="col-2">
                    <img class="profile-img" src="../assets/profile/eko.jpg" alt="">
                </div>
                <div class="col">
                    <h5 class="card-title">Flower</h5>
                    <p class="card-text">
                        Eko Soetriono
                    </p>
                </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col contents">
        <div class="card" style="width: 18rem">
          <img src="../assets/image/leaf.jpg" class="card-img-top" alt="..." />
          <div class="card-body">
            <div class="row"> 
                <div class="col-2">
                    <img class="profile-img" src="../assets/profile/eko.jpg" alt="">
                </div>
                <div class="col">
                    <h5 class="card-title">Leaf</h5>
                    <p class="card-text">
                        Eko Soetriono
                    </p>
                </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NuxtContent',
}
</script>

<style scoped>
* {
    z-index: -99;
}
.container {
    margin-top: 12%;
    z-index: -99;
    display: flex;
    flex-flow: wrap;
    justify-content: center;
    align-content: center;
}
.profile-img {
    border-radius: 50%;
    width: 30px;
}
.foto:hover {
    opacity: 0.2;
}
.card-title{
    text-align: left;
    font-size: 18px;
}
.card-text {
    text-align: left;
    font-size: 14px;
    margin-top: -7px;
}
.row-con {
    margin-top: 10px;
}
.contents {
    margin-top: 10px;
}
</style>