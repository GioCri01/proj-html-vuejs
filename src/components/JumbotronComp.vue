<template>
  <div class="jumbotron position-relative">
    <div class="jumbotron-content ">
      <h1>Lead ~ Customer</h1>
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ut illum sunt similique eum ad praesentium eligendi! Excepturi, cum quibusdam architecto eum accusamus eveniet eaque ea, repellat rerum nulla corrupti iure!</p>
      <button>Get in touch</button>
      <button class="read-more">Read More</button>
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
    
    background-image: url(../assets/img/hero-image.png);
    background-position: center;
    background-size:cover ;
    filter: brightness(0.9);

    p{
      color: #b4b7c2;
    }

    .jumbotron-content{
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%,-50%);
      text-align: center;
       button{
             padding:  15px;
             margin: 0 15px;
             border-radius: 10px;
             text-transform: uppercase;
             background-color:#058283;
             color: white;
             border: none;
         }

         .read-more{
           border: 2px solid #058283;
           background-color: transparent;
         }

         h1{
           font: 800;
           color: rgb(255, 255, 255);
           font-size: 80px;
           font-family:Arial, Helvetica, sans-serif;
         }
    }
  }

</style>