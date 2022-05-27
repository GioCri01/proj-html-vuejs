<template>
  <div >
    <HeaderComp
     :linkList="LinkMenu"
     
    />
    <JumbotronComp/>
    <MainComp/>
    <FooterComp
    
    :footerObj="LinkFooter"
    />
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue';
import JumbotronComp from './components/JumbotronComp.vue';
import LinkMenu from "./assets/data/LinkMenu"; //json
import FooterComp from "./components/FooterComp.vue";
import LinkFooter from "./assets/data/LinkFooter"; //json
import MainComp from './components/MainComp.vue';


export default {
  name: 'App',
  components: {
    HeaderComp,
    JumbotronComp,
    FooterComp,
    MainComp
},

data(){
  return{
    LinkMenu,
    LinkFooter,
  }
},
mounted(){
  console.log(this.LinkMenu);
}


}
</script>

<style lang="scss">
@import "./assets/style/general";
@import url('https://fonts.googleapis.com/css2?family=Tiro+Devanagari+Marathi&display=swap');
body{
 font-family: 'Tiro Devanagari Marathi', serif;
  
}


</style>
