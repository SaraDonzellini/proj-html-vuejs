<script>
export default {
  name: 'BakeryStayTouch'
}
</script>

<template >
  <div class="wrapper">
    <section class="container-fluid">
      <div class="row">
        <div class="col-3">
          <div class="cook"></div>
        </div>
        <div class="col-6">
          <div class="stay-in-touch">
            <h6>
              MADE FOR SHARING
            </h6>
            <h2>
              Let's stay in touch
            </h2>
            <a class="btn mt-5 my_button" href="#"><i class="fa-brands fa-instagram"></i> Follow us</a>
          </div>
        </div>
        <div class="col-3">
          <div class="croissant"></div>
        </div>
      </div>
      <div class="row">
        <div class="col-3">
          <div class="bread"></div>
        </div>
        <div class="col-3">
          <div class="pankakes"></div>
        </div>
        <div class="col-3">
          <div class="bread-chest"></div>
        </div>
        <div class="col-3">
          <div class="cake"></div>
        </div>


      </div>
    </section>

  </div>
</template>

<style lang="scss" scoped>
@use '../../assets/styles/style.scss' as *;
@use '../../assets/styles/partials/_variables.scss' as *;
@use '../node_modules/bootstrap/scss/bootstrap.scss' as *;

h6 {
  font-size: small;
  padding-top: 7rem;
  padding-bottom: 1rem;
}

h2 {
  font-weight: bold;
  color: $daisy-bush;
}

.wrapper {
  height: 100vh;
  width: 90%;
  text-align: center;
  margin: auto;
}

.stay-in-touch {
  width: 830px;
  height: 450px;
  background-color: #f8f1f3;
}

.cook,
.croissant,
.bread,
.pankakes,
.bread-chest,
.cake {
  width: 400px;
  height: 450px;
  margin-bottom: 2rem;
  background-image: url('../../assets/imgs/social-1.jpg');
  background-size: cover;
}

.croissant {
  background-image: url('../../assets/imgs/social-2.jpg');
}

.bread {
  background-image: url('../../assets/imgs/social-3.jpg');
}

.pankakes {
  background-image: url('../../assets/imgs/social-5.jpg');
}

.bread-chest {
  background-image: url('../../assets/imgs/social-4.jpg');
}

.cake {
  background-image: url('../../assets/imgs/social-6.jpg');
}

.my_button {
  font-size: 0.9rem;
  font-weight: bold;
  padding: 0.8rem 1rem;
  background-color: $daisy-bush;
  color: $white-color;

  &:hover {
    background-color: $white-accent;
    color: $daisy-bush;
  }
}
</style>