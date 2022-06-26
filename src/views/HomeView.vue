<template>
  <div class="home">
    <HeaderShaynaVue />
    <HeroShaynaVue />
    <WomanShaynaVue />
    <InstaShaynaVue />
    <PartnerShaynaVue />
    <FooterShaynaVue />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShaynaVue from '@/components/HeaderShayna.vue'
import HeroShaynaVue from '@/components/HeroShayna.vue'
import WomanShaynaVue from '@/components/WomanShayna'
import InstaShaynaVue from '@/components/InstaShayna'
import PartnerShaynaVue from '@/components/PartnerShayna'
import FooterShaynaVue from '@/components/FooterShayna'

export default {
  name: 'HomeView',
  components: {
    HeaderShaynaVue,
    HeroShaynaVue,
    WomanShaynaVue,
    InstaShaynaVue,
    PartnerShaynaVue,
    FooterShaynaVue
}
}
</script>
