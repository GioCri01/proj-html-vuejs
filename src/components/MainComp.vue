<template>
  <main>
      <WhiteCard/>
  </main>
</template>

<script>

import WhiteCard from './mainComponent/WhiteCard.vue'

export default {
name:"MainComp",
components:{
    WhiteCard,
}
}
</script>

<style lang="scss" scoped>
main{
    width: 100%;
}

</style>