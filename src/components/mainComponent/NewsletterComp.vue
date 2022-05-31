<template>
  <section class="d-flex justify-content-center align-items-center">
      <div class="container ">
          <div class="row ">
              <div class="col-6">
                    <div class="title-comp">
                        <span class="pre-title">Newsletter</span>
                         <h2> <span class="special-style">Know</span> First</h2>
                        <div class="d-flex justify-content-between">
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta dolore ducimus omnis repudiandae</p>
                            
                        </div>
                    </div>
              </div>
              <div class="col-6  flex-column">
                  <input  class=" form-control " placeholder="Nome" type="text">
                  <input class=" form-control"  placeholder="email" type="text">
                  <button>subscribe</button>
              </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name:"newsletterComp",

}
</script>

<style lang="scss" scoped>
section{
    width: 100%;
    height: 500px;
    background-image: url(../../assets/img/bg-1.jpg);
    background-position: center;
    background-size: cover;

     button{
             padding: 10px 30px;
             border-radius: 10px;
             text-transform: uppercase;
             background-color: #058283;
             color: white;
             border: none;
             text-transform: uppercase;
         }

         input{
             width: 70%;
             margin: 20px 0;
             padding: 10px 10px;
             background-color: #c3cdcd93 ;
             border: none;
         }

          .title-comp{
        padding: 15px;
        color: white;

        .pre-title{
            text-transform: uppercase;
            color: #009ea0;
        }

        h2{
        font-size:60px ;
        margin: 20px 0;

        .special-style{
        display: inline-block;
        background-color:#173338 ;
        
        padding: 10px 18px;
        border-radius: 5px;
        
            }
        }

        p{
            color: gray;
        }



    }
}

</style>