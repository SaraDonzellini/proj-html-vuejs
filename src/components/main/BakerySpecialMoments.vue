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
            <img src="../../assets/imgs/corporate-bg.jpg" alt="" class="vanish">
            <img src="../../assets/imgs/corporate-hover-bg.jpg" alt="" class="none">
            <div class="text none">
              <h6>INTERNATIONAL BAKERY</h6>
              <h1>Corporate Events</h1>
              <a class="btn mt-5 my_button" href="#">Explore More</a>
            </div>

          </div>
        </div>
        <div class="col-6">
          <div class="box">
            <img src="../../assets/imgs/wedding-bg.jpg" alt="" class="vanish">
            <img src="../../assets/imgs/wedding-hover-bg.jpg" alt="" class="none">
            <div class="text none">
              <h6>PRIVATE DINING HALL</h6>
              <h1>Weddings & Parties</h1>
              <a class="btn mt-5 my_button" href="#">Explore More</a>
            </div>
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
  position: relative;
  
  img {
    width: 100%;
  }
  
  &:hover .none {
    display: inline;
  }

  &:hover .vanish {
    display: none;
  }
}

.text {
  position: absolute;
  text-align: center;
  color: white;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.none {
  display: none;
  z-index: 1;
}


.my_button {
  font-size: 0.9rem;
  background-color: $daisy-bush;
  color: $white-color;
  font-family: 'Work Sans', sans-serif;
  font-weight: bold;

  &:hover {
    background-color: $white-accent;
    color: $daisy-bush;
  }
}
</style>