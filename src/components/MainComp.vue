<template>
  <main>
      <WhiteCard/>
      <CompanyComp/>
      <ServicesComp/>
      <PricingComp/>
      <LatestnewsComp/>
  </main>
</template>

<script>

import WhiteCard from './mainComponent/WhiteCard.vue'
import CompanyComp from './mainComponent/CompanyComp.vue'
import ServicesComp from './mainComponent/ServicesComp.vue'
import PricingComp from './mainComponent/PricingComp.vue'
import LatestnewsComp from './mainComponent/LatestnewsComp.vue'

export default {
name:"MainComp",
components:{
    WhiteCard,
    CompanyComp,
    ServicesComp,
    PricingComp,
    LatestnewsComp
}
}
</script>

<style lang="scss" scoped>
main{
    width: 100%;
}

</style>