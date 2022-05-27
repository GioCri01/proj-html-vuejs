<template>
  <div >
    <HeaderComp/>
    <JumbotronComp/>
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue';
import JumbotronComp from './components/JumbotronComp.vue';


export default {
  name: 'App',
  components: {
    HeaderComp,
    JumbotronComp
}
}
</script>

<style lang="scss">
@import "./assets/style/general";
</style>
