<script>
import BakeryDelivery from './components/footer/BakeryDelivery.vue';
import BakeryFooter from './components/footer/BakeryFooter.vue';
import BakeryHeaderVue from './components/header/BakeryHeader.vue'
import BakeryBlocks from './components/main/BakeryBlocks.vue';
import BakeryForYou from './components/main/BakeryForYou.vue';
import BakeryOurBakeries from './components/main/BakeryOurBakeries.vue';
import BakeryProducts from './components/main/BakeryProducts.vue';
import BakerySpecialMoments from './components/main/BakerySpecialMoments.vue';
import BakeryStayTouch from './components/main/BakeryStayTouch.vue';

export default {
  name: 'AppVue',
  components: {
    BakeryHeaderVue,
    BakeryProducts,
    BakerySpecialMoments,
    BakeryForYou,
    BakeryBlocks,
    BakeryOurBakeries,
    BakeryStayTouch,
    BakeryDelivery,
    BakeryFooter
  }

}
</script>

<template>
  <header>
    <BakeryHeaderVue />
  </header>
  <main>
    <BakeryProducts />
    <BakerySpecialMoments />
    <BakeryForYou />
    <BakeryBlocks />

  </main>
  <footer>
    <BakeryOurBakeries />
    <BakeryStayTouch />
    <BakeryDelivery />
    <BakeryFooter />
  </footer>
</template>

<style lang="scss">
@use './assets/styles/style.scss' as *;
@use './assets/styles/partials/_variables.scss' as *;
@use '../node_modules/bootstrap/scss/bootstrap.scss' as *;
</style>
