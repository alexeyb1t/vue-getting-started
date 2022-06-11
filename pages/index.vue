<template>
  <div>
    <div class="block">
      <hero-banner/>
    </div>

    <div class="block">
      <promotion-section/>
    </div>
  </div>
</template>

<script>
import HeroBanner from '../components/index/hero-banner';
import PromotionSection from '../components/index/promotion-section';
export default {
  name: 'IndexPage',
  components: {PromotionSection, HeroBanner},
}
</script>
