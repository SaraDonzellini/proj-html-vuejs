<script>
export default {
  name: 'BakeryOurBakeries'
}
</script>

<template >
  <div class="wrapper">
    <section class="container-fluid">
      <div class="row">
        <div class="col-12">
          <h6>
            LOCATIONS
          </h6>
          <h2 class="mb-5">
            Visit our Bakeries
          </h2>
        </div>

      </div>
    </section>
    <section class="container-fluid">
      <div class="row flex">
        <div class="col-6">
          <div class="newyork-store"></div>
        </div>
        <div class="col-6">
          <div class="london-store"></div>
        </div>
      </div>
    </section>
    <section class="container-fluid">
      <div class="row">
        <div class="col-6">
          <div class="newyork-store-contacts">
            <h2 class="pt-5">
              New York
            </h2>
            <div class="contacts_wrapper flex">
              <div class="call-us">
                <h6>CALL US</h6>
                <p>1.800.458.556</p>
              </div>
              <div class="all-week">
                <h6>OPEN ALL WEEK</h6>
                <p>9:00 AM - 6:00 PM</p>
              </div>
              <div class="map">
                <a class="btn my_button" href="#">Show Map</a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-6">
          <div class="london-store-contacts">
            <h2 class="pt-5">
                London
            </h2>
            <div class="contacts_wrapper flex">
              <div class="call-us">
                <h6>CALL US</h6>
                <p>1.800.458.556</p>
              </div>
              <div class="all-week">
                <h6>OPEN ALL WEEK</h6>
                <p>9:00 AM - 6:00 PM</p>
              </div>
              <div class="map">
                <a class="btn my_button" href="#">Show Map</a>
              </div>
            </div>

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

h6 {
  font-size: small;
}

h2 {
  font-weight: bold;
  color: $daisy-bush;
}

.flex{
  display: flex;
}
.wrapper {
  margin-top: 5rem;
  height: 100vh;
  width: 90vw;
  text-align: center;
  
  margin-left: 4rem;
}

.newyork-store,
.london-store {
  width: 45vw;
  height: 55vh;
}

.newyork-store {
  // margin-left: 4rem;
  background-image: url('../../assets/imgs/new-york-bk-800x530.jpg');
  background-size: cover;

}

.london-store {
  
  // margin-left: 4rem;
  background-image: url('../../assets/imgs/london-bk-800x530.jpg');
  background-size: cover;

}

.newyork-store-contacts{
  background-color: $new-york;
  width: 45vw;
  height: 25vh;
}

.london-store-contacts{
  background-color: $london;
  width: 45vw;
  height: 25vh;
}
.my_button{
    font-size: 0.9rem;
    background-color: $white-color;
    color: $daisy-bush;

    &:hover {
      background-color: $daisy-bush;
      color: $white-color;
    }
  }

.contacts_wrapper{
  margin-top: 2rem;
  justify-content: space-evenly;
}
</style>