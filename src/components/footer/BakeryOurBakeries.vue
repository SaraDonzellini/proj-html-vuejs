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
          <h2>
            Visit our Bakeries
          </h2>
        </div>

      </div>
    </section>
    <section class="container-fluid">
      <div class="row">
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
        <div class="col-6"></div>
        <div class="col-6"></div>
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

.wrapper {
  margin-top: 5rem;
  height: 100vh;
  text-align: center;
}
</style>