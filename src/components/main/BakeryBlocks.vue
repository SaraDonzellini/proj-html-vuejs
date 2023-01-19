<script>
export default {

}
</script>

<template >
  <div class="wrapper">
    <section class="container-fluid">
      <div class="row">
        <div class="col-12">
          <div class="tell-us">
            <div class="gradient">
              <div class="container-fluid">
                <div class="row flex space-between">
                  <div class="col-5">
                    <h1>
                      Tell us what you have in mind
                    </h1>
                  </div>
                  <div class="col-5 flex flex-column space-between">
                    <h2>
                      01
                    </h2>
                    <h6>
                      MANUAL INGREDIENTS SELECTION
                    </h6>
                    <p>
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio beatae similique dolorum ab
                      laborum repudiandae ut cupiditate animi numquam magni incidunt eligendi nostrum iste dolor velit
                      repellendus, praesentium laudantium error.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="container-fluid">
      <div class="row flex space-evenly">
        <div class="col-5">
          <div class="block-left tell-us">
            <div class="gradient">
              <div class="container-fluid">
                <div class="row flex ">
                  <div class="col-9">
                    <h1>
                      We Start Baking
                    </h1>
                    <h6 class="delivered">
                      SWEET & DELICIOUS
                    </h6>
                    <p class="delivered">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio beatae similique dolorum ab
                      laborum repudiandae ut cupiditate animi.
                    </p>
                  </div>
                  <div class="col-3">
                    <h2>
                      02
                    </h2>
                  </div>
                </div>
              </div>
            </div>

          </div>
        </div>
        <div class="col-5">
          <div class="block-right">
            <h6 class="text-block">
              DONT JUST TAKE OUR WORD FOR IT
            </h6>
            <h3>
              "Finally found an alternative to the mass produced products. Something that incorporatesreal organic
              ingredients, nutrient dense wellness while promoting sustainability and activity."
            </h3>
            <h5>
              Rachel Cooper, Founder
            </h5>
          </div>
        </div>
      </div>
    </section>

    <section class="container-fluid">
      <div class="row">
        <div class="col-12">
          <div class="tell-us to-you">
            <div class="gradient">
              <div class="container-fluid">
                <div class="row flex space-between">
                  <div class="col-5">
                    <h1>
                      Delivered to your home
                    </h1>
                    <h6 class="delivered">
                      BAKED TO ORDER & GIFT WRAPPED
                    </h6>
                    <p class="delivered">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio beatae similique dolorum ab
                      laborum repudiandae ut cupiditate animi numquam magni incidunt eligendi nostrum iste dolor velit
                      repellendus, praesentium laudantium error.
                    </p>
                  </div>
                  <div class="col-5">
                    <h2>
                      03
                    </h2>
                  </div>
                </div>
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

h1,
h2 {
  margin: 5rem;
}

h1 {
  font-weight: bold;
  font-size: 4rem;
}

h2 {
  font-weight: 400;
  font-size: 5rem;
  text-align: end;
}

h3 {
  font-weight: bold;
  font-size: 3rem;
  color: $daisy-bush;
}

h5 {
  font-size: 1rem;
}

h6 {
  margin-top: 20rem;
  font-size: small;
}

h6.text-block {
  margin-top: 1rem;
}

p {
  font-size: 1.5rem;
  margin-right: 4rem;
}

.delivered {
  margin-left: 5rem;
}

.flex {
  display: flex;
}

.space-between {
  justify-content: space-between;
}

.space-evenly {
  justify-content: space-around;
}

.flex-column {
  flex-direction: column;
}

.tell-us {
  color: $white-color;
  width: 90vw;
  height: 90vh;
  background-image: url('../../assets/imgs/bakery-process-1.jpg');
  background-size: cover;
  margin: 0 auto;


  .gradient {
    width: 100%;
    height: 100%;
    background: linear-gradient(0deg, rgba(0, 0, 0, 0.70) 0%, rgba(0, 0, 0, 0.50) 100%);
  }

}

.block-left {
  margin-top: 4rem;
  width: 40vw;
  height: 40vw;
  background-image: url('../../assets/imgs/bakery-process-2.jpg');
  background-size: cover;


  .gradient {
    width: 100%;
    height: 100%;
    background: linear-gradient(0deg, rgba(0, 0, 0, 0.70) 0%, rgba(0, 0, 0, 0.50) 100%);
  }
}

.block-right {
  padding: 5rem;
  margin-top: 4rem;
  width: 40vw;
  height: 40vw;
  background-color: $white-accent;
}

.to-you {
  margin-top: 4rem;
  background-image: url('../../assets/imgs/bakery-process-3.jpg');
  background-size: cover;

}
</style>