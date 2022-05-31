<template>
  <main>
      <WhiteCard/>
      <CompanyComp/>
      <ServicesComp/>
      <PricingComp/>
      <LatestnewsComp/>
      <NewsletterComp/>
      <FormComp/>
  </main>
</template>

<script>

import WhiteCard from './mainComponent/WhiteCard.vue'
import CompanyComp from './mainComponent/CompanyComp.vue'
import ServicesComp from './mainComponent/ServicesComp.vue'
import PricingComp from './mainComponent/PricingComp.vue'
import LatestnewsComp from './mainComponent/LatestnewsComp.vue'
import NewsletterComp from './mainComponent/NewsletterComp.vue'
import FormComp from './FormComp.vue'

export default {
name:"MainComp",
components:{
    WhiteCard,
    CompanyComp,
    ServicesComp,
    PricingComp,
    LatestnewsComp,
    NewsletterComp,
    FormComp
}
}
</script>

<style lang="scss" scoped>
main{
    width: 100%;
}

</style>