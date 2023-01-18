<script>
export default {
  name: 'BakerySpecialMoments'
}
</script>

<template >
  <div class="wrapper">
    <div class="container-fluid">
      <div class="row">
        <div class="col-12">
          <div class="title_container">
            <h6>
              CORPORATE & WEDDINGS
            </h6>
            <h2>
              Baking Special Moments
            </h2>

          </div>
        </div>
      </div>
    </div>
    <div class="container-fluid">
      <div class="row flex">
        <div class="col-6">
          <div class="box">
            <img src="../../assets/imgs/corporate-bg.jpg" alt="">
            <img src="../../assets/imgs/corporate-hover-bg.jpg" alt="" class="d-none">
          </div>
        </div>
        <div class="col-6">
          <div class="box">
            <img src="../../assets/imgs/wedding-bg.jpg" alt="">
            <img src="../../assets/imgs/wedding-hover-bg.jpg" alt="" class="d-none">

          </div>

        </div>
      </div>
    </div>

  </div>
</template>

<style lang="scss" scoped>
@use '../../assets/styles/style.scss' as *;
@use '../../assets/styles/partials/_variables.scss' as *;
@use '../node_modules/bootstrap/scss/bootstrap.scss' as *;

h6 {
  font-size: small;
}

h2 {
  font-weight: bold;
  color: $daisy-bush;
  margin-bottom: 3rem;
}

.flex {
  display: flex;

}

.wrapper {
  height: 100vh;
}

.title_container {
  text-align: center;
}

.box {
  width: 45vw;
  margin: auto;

  img {
    width: 100%;
  }
}
</style>