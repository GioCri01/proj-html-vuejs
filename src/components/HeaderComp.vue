<template>
  <header>
      <div class="header-top"></div>
      <div class="header-menu d-flex align-items-center">
          <div class="container d-flex justify-content-between  ">
              <div class="logo">
                <img src="../assets/img/logo_48.png" alt="">
                </div>
                <div class="menu d-flex">
                    <ul class="d-flex">
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                    </ul>
                    <button>bottone</button>
                </div>
          </div>
      </div>
  </header>
</template>

<script>
export default {
name:"HeaderComp",
}
</script>

<style lang="scss" scoped>
 header{
     position: fixed;
     z-index: 999;
     width: 100%;
     height: 120px;
     

     .header-top{
         height: 40px;
         background-color: #21333e;
     }

     .header-menu{
         height: calc(120px - 40px);
         ul{
             margin-right:20px ;
             list-style: none;
             li{
                 padding: 0 30px;
                 text-transform: uppercase;
                 a{
                     color: white;
                    text-decoration: none;
                 }
             }
         }

         button{
             padding: 0 30px;
             border-radius: 10px;
             text-transform: uppercase;
             background-color: blue;
             border: none;
         }
     }
 }

</style>