<script>
export default {
  name: 'BakeryHeader'
}
</script>

<template>
  <header>

    <section class="container-fluid">
      <div class="row">
        <div class="col-12">
          <div class="box flex">
            <div class="logo">
              <img class="m-3" src="../../assets/imgs/avada-bakery-logo.png" alt="avada bakery logo">
            </div>
            <nav>
              <ul class="flex">
                <li class="active">HOME</li>
                <li>SHOP</li>
                <li>ABOUT</li>
                <li>GALLERY</li>
                <li>LOCATIONS</li>
                <li>JOURNAL</li>
                <li>CONTACT</li>
                <li>MYACCOUNT</li>
                <li><i class="fa-solid fa-cart-shopping"></i></li>
              </ul>
            </nav>

          </div>
        </div>
      </div>
    </section>
    <section class="container-fluid">
      <div class="row">
        <div class="col-4">
          <div class="title-container">
            <h6>FRESH & TASTY BAKERY EVERY DAY</h6>
            <h1>The Perfect Fresh Bread</h1>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Repudiandae, dolor ab quis maiores, architecto
              quisquam amet sequi eaque nisi ipsa eius corporis, nulla molestiae.</p>

            <a class="btn mt-5 my_button" href="#">Explore our products</a>
          </div>

        </div>
      </div>

    </section>
  </header>
</template>

<style lang="scss" scoped>
@use '../../assets/styles/style.scss' as *;
@use '../../assets/styles/partials/_variables.scss' as *;
@use '../node_modules/bootstrap/scss/bootstrap.scss' as *;

header {
  height: 100vh;
  background-image: url('../../assets/imgs/hero-header-bakery.jpg');
  background-size: cover;
}

.flex {
  display: flex;
  justify-content: space-between;
}

ul {
  list-style-type: none;
  margin-right: 3rem;
  margin-top: 2.5rem;
  font-size: 0.8rem;
  font-weight: 600;
  color: $daisy-bush;

  li {
    margin: 1rem;

    &:hover {
      border-bottom: 1px solid $daisy-bush;
    }
  }
}

h1 {
  font-weight: bold;
  font-size: 3rem;
  color: $daisy-bush;
  margin-top: 1rem;
}

h6,
p {
  color: $manatee-gray;
}

h6 {
  font-size: small;
}

p {
  font-size: large;
  margin-top: 1rem;
}

.title-container {
  margin-top: 12rem;
  margin-left: 6rem;
}

.active {
  border-bottom: 1px solid $daisy-bush;
}

.my_button {
  font-size: 0.9rem;
  background-color: $white-color;
  color: $daisy-bush;

  &:hover {
    background-color: $daisy-bush;
    color: $white-color;
  }
}
</style>