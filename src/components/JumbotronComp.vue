<template>
  <div class="jumbotron position-relative">
    <div class="jumbotron-content ">
      <h1>Lead ~ Customer</h1>
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ut illum sunt similique eum ad praesentium eligendi! Excepturi, cum quibusdam architecto eum accusamus eveniet eaque ea, repellat rerum nulla corrupti iure!</p>
      <button>Get in touch</button>
      <button>Read More</button>
    </div>
  </div>
</template>

<script>
export default {
 name:"JumbotronComp",
}
</script>

<style lang="scss" scoped>
  .jumbotron{
    width: 100%;
    height: 800px;
    
    background-image: url(../assets/img/Polygon\ Luminary.svg);
    background-position: center;
    background-size:cover ;
    filter: brightness(0.7);

    .jumbotron-content{
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%,-50%);
      text-align: center;

    }
  }

</style>