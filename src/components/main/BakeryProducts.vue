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
              All our delectable pastries are backed fresh in our kitchen every morning, and are made with all-natural,
              all organic ingredients.
            </h2>
            <a class="btn mt-5 my_button" href="#">Start shopping</a>
          </div>
        </div>
        <div class="col-3">
          <div class="my_container">
            <img src="../../assets/imgs/choco-chip-cookies-500x638.jpg" alt="choco chip cookies">
            <div class="my_hover none">
              <h2>
                Choco Chip Cookies
              </h2>
              <h6>
                Cookies, Pastries
              </h6>
              <h4>&dollar;19.00 &dollar;39.00</h4>
            </div>
            <div class="scroll">
              <p class="mt-4">&lt</p>
            </div>
          </div>
        </div>
        <div class="col-3">
          <div class="my_container">
            <img src="../../assets/imgs/strawberry-jam-cookies-500x638.jpg" alt="strawberry jam cookies">
            <div class="my_hover none">
              <h2>
                Strawberry Jam Cookies
              </h2>
              <h6>
                Cookies, Pastries
              </h6>
              <h4>&dollar;24.00 &dollar;62.00</h4>
            </div>
            <div class="my_scroll">
              <p class="mt-4"> ></p>
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
}

h4 {
  font-family: 'Work Sans', sans-serif;
}

.flex {
  display: flex;
  justify-content: space-evenly;
}

.wrapper {
  height: 100vh;
}

.my_container {
  margin-top: 8rem;
  position: relative;

  img {
    width: 100%;
    height: 100%;
  }

  &:hover .none {
    display: block;
  }
}

.scroll {
  height: 5rem;
  width: 2rem;
  background-color: $lavanda;
  position: absolute;
  bottom: 45%;
  color: white;

  p {
    margin-left: 0.5rem;
  }
}

.my_scroll {
  height: 5rem;
  width: 2rem;
  background-color: $lavanda;
  position: absolute;
  bottom: 45%;
  right: 0%;
  color: white;

  p {
    margin-left: 0.5rem;
  }
}

.my_hover {
  color: white;
  position: absolute;
  text-align: center;
  height: 100%;
  width: 100%;
  top: 0%;
  background-color: rgba(0, 0, 0, 0.133);

  h2 {
    margin-top: 15rem;
    color: white;
  }
}

.none {
  display: none;


}

.my_button {
  font-size: 0.9rem;
  background-color: $daisy-bush;
  color: $white-color;

  &:hover {
    background-color: $white-accent;
    color: $daisy-bush;
  }
}
</style>