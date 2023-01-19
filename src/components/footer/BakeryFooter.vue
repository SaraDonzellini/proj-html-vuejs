<script>
export default {
  name: 'BakeryFooter'
}
</script>

<template >
  <div class="wrapper">

    <section class="container-fluid">
      <div class="row">
        <div class="col-6">
          <div class="navbar">
            <div class="logo">
              <img src="../../assets/imgs/avada-bakery-logo.png" alt="">
            </div>
            <nav>
              <ul class="d-flex">
                <li>Shop</li>
                <li>About</li>
                <li>Gallery</li>
                <li>Locations</li>
                <li>Journal</li>
                <li>Contact</li>
                <li>Orders</li>
                <li><i class="fa-solid fa-cart-shopping"> </i><span class="shopping-cart-num">0</span></li>
              </ul>
            </nav>
          </div>
        </div>
        <div class="col-6">
          <div class="contacts">
            <h2>
              Subscribe to our newsletter
            </h2>
            <div class="button">
              <input type="text" placeholder="Enter email address*">
              <a class="btn my_button" href="#">Subscribe</a>
            </div>
          </div>
        </div>
      </div>
      <div class="row flex">
        <div class="col-6">
          <div class="copyright">
            <p>&copy; Copyright 2012 - 2020 | Avada Theme by ThemeFusion | All Rights Reserved | Powered by WordPress
            </p>
          </div>
        </div>
        <div class="col-6">
          <div class="socials">
            <i class="fa-brands fa-instagram"></i><i class="fa-brands fa-twitter"></i><i
              class="fa-brands fa-facebook-f"></i><i class="fa-brands fa-pinterest-p"></i>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style lang="scss" scoped>
@use '../../assets/styles/style.scss' as *;
@use '../../assets/styles/partials/_variables.scss' as *;
@use '../node_modules/bootstrap/scss/bootstrap.scss' as *;

h2 {
  color: $daisy-bush;
  font-weight: bold;
  font-size: x-large;
  margin-bottom: 2rem;
}

p {
  margin: 5rem;
  color: $daisy-bush;
  font-size: 0.8rem;
}

.socials {
  margin: 5rem;
  margin-left: 35rem;
  color: $daisy-bush;

  i {
    padding-left: 3rem;
  }
}

.flex {
  display: flex;
  justify-content: space-between;
}

.wrapper {
  height: 50vh;
}

.navbar {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.shopping-cart-num {
  background-color: #eeeaf3;
  border-radius: 50%;

}

.contacts {
  margin: 5rem;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
}

.logo {
  margin: 3rem;
}

ul {
  margin-top: 2rem;
  list-style-type: none;
  font-family: 'Work Sans', sans-serif;
  color: $daisy-bush;

  li {
    margin-left: 3rem;
  }
}

input {
  border-radius: 3px;
  border: 1px solid #ececed;
  padding: 0.8rem 1rem;
  margin-right: 2rem;
  width: 500px;
}

.my_button {
  font-size: 1rem;
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