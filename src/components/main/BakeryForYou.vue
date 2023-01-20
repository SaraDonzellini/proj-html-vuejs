<script>
export default {
  name: 'BakeryForYou'
}
</script>

<template >
  <div class="wrapper">
    <div class="container-fluid">
      <div class="row flex">
        <div class="col-4">
          <div class="title_container">
            <h2>
              Find a freshly baked product perfect for you
            </h2>
            <p>
              Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nemo, debitis. Lorem ipsum dolor sit amet.
            </p>
            <a class="btn mt-5 my_button" href="#">Shop all products</a>
          </div>
        </div>
        <div class="col-2">
          <div class="my_container">
            <img src="../../assets/imgs/choco-chip-cookies-400x510.jpg" alt="choco chip cookies">
            <div class="my_scroll">
              <p class="mt-4"> &lt</p>
            </div>
            <h3>
              Choco Chip Cookies
            </h3>
            <h5>
              &dollar;19.00 - &dollar;39.00
            </h5>
            <div class="my_hover none">
              <h6>
                SELECT OPTIONS / QUICK VIEW
              </h6>
            </div>
          </div>
        </div>
        <div class="col-2">
          <div class="my_container">
            <img src="../../assets/imgs/strawberry-jam-cookies-400x510.jpg" alt="strawberry jam cookies">
            <h3>
              Strawberry Jam Cookies
            </h3>
            <h5>
              &dollar;24.00 - &dollar;62.00
            </h5>
            <div class="my_hover none">
              <h6>
                SELECT OPTIONS / QUICK VIEW
              </h6>
            </div>
          </div>
        </div>
        <div class="col-2">
          <div class="my_container">
            <img src="../../assets/imgs/strawberry-donut-400x510.jpg" alt="strawberry donut">
            <h3>
              Strawberry Donut
            </h3>
            <h5>
              &dollar;24.00 - &dollar;42.00
            </h5>
            <div class="my_hover none">
              <h6>
                SELECT OPTIONS / QUICK VIEW
              </h6>
            </div>
          </div>
        </div>
        <div class="col-2">
          <div class="my_container">
            <img src="../../assets/imgs/perfect-macarons-400x510.jpg" alt="perfect macarons">
            <div class="scroll">
              <p class="mt-4"> > </p>
            </div>
            <h3>
              Perfect Macarons
            </h3>
            <h5>
              &dollar;18.00 - &dollar;52.00
            </h5>
            <div class="my_hover none">
              <h6>
                SELECT OPTIONS / QUICK VIEW
              </h6>
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



h2,
h3 {
  font-weight: bold;
  color: $daisy-bush;
  font-family: 'Source Serif Pro', serif;

}

h5 {
  color: $daisy-bush;
  font-family: 'Work Sans', sans-serif;
}

p {
  font-size: large;
  margin-top: 1rem;
}

.flex {
  display: flex;
  justify-content: space-evenly;
  // align-items: center;
}

.wrapper {
  height: 90vh;

}

.title_container {
  margin-left: 4rem;
  margin-top: 15rem;
  text-align: center;
}

.my_container {
  width: 15vw;
  text-align: center;
  position: relative;
  height: 100%;

  &:hover .none {
    display: block;
  }

  img {
    width: 100%;
    margin-top: 10rem;
  }
}

.my_scroll {
  height: 5rem;
  width: 2rem;
  background-color: $lavanda;
  position: absolute;
  bottom: 25%;
  color: white;

  p {
    margin-left: 0.5rem;
  }
}

.scroll {
  height: 5rem;
  width: 2rem;
  background-color: $lavanda;
  position: absolute;
  bottom: 25%;
  right: 0;
  color: white;

  p {
    margin-left: 0.5rem;
  }
}

.my_hover {
  position: absolute;
  top: 25%;
  left: 0;
  color: white;
  height: 58%;
  width: 100%;
  padding-top: 60%;
  background-color: rgba(0, 0, 0, 0.133);
}

.none {
  display: none;
}

.my_button {
  font-size: 0.9rem;
  padding: 0.5rem 1rem;
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