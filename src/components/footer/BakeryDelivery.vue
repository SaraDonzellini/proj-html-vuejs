<script>
export default {
  name: 'BakeryDelivery'
}
</script>

<template>
  <div class="wrapper">
    <div class="container-fluid">
      <div class="row">
        <div class="col-2"></div>
        <div class="col-5">
          <div class="title-container">
            <h6>
              TRY OUR SEASONAL PRODUCTS
            </h6>
            <h2>
              Order for pick-up or delivery to your home
            </h2>
            <a class="btn my_button" href="#">Shop now</a>
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
  margin-top: 5rem;
  font-size: small;
  color: $white-color
}

h2 {
  margin-top: 1rem;
  font-weight: bold;
  font-size: 3rem;
  color: $white-color;
}

.my_button {
  margin-top: 4rem;
  font-size: 1rem;
  font-weight: bold;
  padding: 1rem;
  width: 200px;
  background-color: $white-color;
  color: $daisy-bush;
  font-family: 'Work Sans', sans-serif;


  &:hover {
    background-color: $daisy-bush;
    color: $white-color;
  }
}

.wrapper {
  background-image: url('../../assets/imgs/call-to-action-bg.jpg');
  background-size: cover;
  height: 50vh;
  margin-top: 5rem;
}

.title-container {
  display: flex;
  flex-direction: column;
  justify-content: center;

}
</style>