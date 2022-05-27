<template>
  <footer>
      <div class="container py-5">
          <div class="row">
              <div class="col-3 offset-1">
                  <img  class=" mb-3" src="../assets/img/logo_48.png" alt="">
                  <p>A Functional HTML . Template for Corporate & Business</p>
                  <ul>
                      <li><i class="fa-solid fa-phone"></i> 1 (305) 1234-5678</li>
                      <li><i class="fa-solid fa-envelope"></i> hello@example.com</li>
                      <li><i class="fa-solid fa-location-dot"></i>  Main Avenue,987</li>
                  </ul>
                  <button>Get In Touch</button>
              </div>
              <div 
              v-for="(footerObj,index) in footerObj"
              :key="`footerObj-${index}`"
              class="col-2 list-container">
                  <h3>{{footerObj.nome}}</h3>
                  <ul>
                      <li
                      v-for="(link,index) in footerObj.linkList"
                      :key="`link-${index}`"
                      ><i class="fa-solid fa-chevron-right"></i><a :href="link.href"> {{link.nome}}</a></li>
                      
                  </ul>
              </div>
              

              
          </div>
      </div>
  </footer>
</template>

<script>

export default {
    name:"FooterComp",
    props:{
        footerObj: Array,
    },

    mounted(){
        console.log(this.footerObj);
    }

}
</script>

<style lang="scss" scoped>
footer{
    width: 100%;
    height: 500px;//provvisorio
    background-color: black;
    color: #9facb1;
    
    ul{
        list-style: none;
        li{
            padding: 5px 0;
            a{
                text-decoration: none;
                color:#9facb1;
            }
        }
    }

    .list-container{
        
        background-color:#19191f;
        border-radius:10px ;
        padding: 10px ;
        margin: 0 20px;
        h3{
            color: white;
            text-align: center;
        }
    }

    button{
             padding: 15px 30px;
             border-radius: 10px;
             border: 1px solid #076b6d;
             text-transform: uppercase;
             background-color: transparent;
             
             color: white;
         }
}

</style>