<script>
export default {
  name: 'BakeryProducts'
}
</script>

<template >
  <div class="wrapper">
    <div class="container-fluid">
      <div class="row flex">
        <div class="col-3">
          <div class="my_container">
            <h6>
              OUR PRODUCTS
            </h6>
            <h2>
              All our delectable pastries are backed fresh in our kitchen every morning, and are made with all-natural, all organic ingredients.
            </h2>
            <a class="btn mt-5 my_button" href="#">Start shopping</a>
          </div>
        </div>
        <div class="col-3">
          <div class="my_container">
            <img src="../../assets/imgs/choco-chip-cookies-500x638.jpg" alt="choco chip cookies">
          </div>
        </div>
        <div class="col-3">
          <div class="my_container">
            <img src="../../assets/imgs/strawberry-jam-cookies-500x638.jpg" alt="strawberry jam cookies">
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

  h6{
    font-size: small;
  }
  h2{
    font-weight: bold;
    color: $daisy-bush;
  }
  .flex{
    display: flex;
    justify-content: space-evenly;
  }
  .wrapper{
    height: 100vh;
  }

  .my_container{
    margin-top: 8rem;
  }
  .my_button{
    font-size: 0.9rem;
    background-color: $daisy-bush;
    color: $white-color;
    &:hover{
      background-color: $white-accent;
      color: $daisy-bush;
    }
  }
</style>