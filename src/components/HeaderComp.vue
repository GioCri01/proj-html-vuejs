<template>
  <header>
      <div class="header-top pt-2 ">
          <div class="container d-flex justify-content-between align-items-center">
              <div class="open-hours">
              <span><i class="fa-solid fa-clock"></i> Open Hours : Mon-Sat 9:00 - 18:00</span>
               </div> 
               <div class="contacts d-flex ">
                   <span><i class="fa-solid fa-phone"></i> 1 (305) 1234-5678</span>
                   <span><i class="fa-solid fa-envelope"></i> hello@example.com</span>
                   <div class="social">
                        <i class="fa-brands fa-facebook-f"></i>
                        <i class="fa-brands fa-twitter"></i>
                        <i class="fa-brands fa-linkedin-in"></i>
                   </div>
                   
               </div>
          </div>
      </div>
      <div class="header-menu d-flex align-items-center">
          <div class="container d-flex justify-content-between mt-3 ">
              <div class="logo">
                <h1><span>Nex</span>Gen</h1>
                </div>
                <div class="menu d-flex">
                    <ul class="d-flex">
                        <li v-for="(link,index) in linkList" :key="`link-${index}`"><a :href="link.href">{{link.nome}}</a></li>
                        
                    </ul>
                    <button>Get in Touch</button>
                </div>
          </div>
      </div>
  </header>
</template>

<script>
export default {
name:"HeaderComp",

props:{
    linkList :Array,
},

mounted(){
    console.log(this.linkList);
}
}
</script>

<style lang="scss" scoped>
 header{
     position: relative;
     z-index: 999;
     width: 100%;
     height: 120px;

     .logo{
         h1{
             color: white;
         }
         span{
             display: inline-block;
             background-color: #354c50b6 ;
             color: #01a3a4;
             padding: 10px 20px;
             border-radius: 20px 0px 0px 20px;
             margin-right:2px ;
         }
     }
     

     .header-top{
         height: 40px;
         background-color: #21333e;
         color: #c0c3d0;
         i{
             margin: 0 15px;
         }
     }

     .header-menu{
         height: calc(120px - 40px);
         ul{
             margin-right:20px ;
             list-style: none;
             padding-top: 10px  ;
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
             background-color: #058283;
             color: white;
             border: none;
         }
     }
 }

</style>