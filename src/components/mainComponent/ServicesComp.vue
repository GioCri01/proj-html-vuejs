<template>
  <section>
      <div class="container py-5">
          <div class="title-comp">
              <span class="pre-title">our business areas</span>
              <h2>Excellence in <span class="special-style">Services</span></h2>
              <div class="d-flex justify-content-between">
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta dolore ducimus omnis repudiandae</p>
                  <button>see all</button>
              </div>
          </div>
          <div class="box-container d-flex justify-content-between flex-wrap">
              <div class="box">
                  <i class="fa-solid fa-cubes"></i>
                  <h3>audit & Assurance</h3>
                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi maiores explicabo ipsum non earum? </p>
                  <button> Read More</button>
              </div>
              <div class="box ">
                  <i class="fa-solid fa-briefcase"></i>
                  <h3>audit & Assurance</h3>
                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi maiores explicabo ipsum non earum? </p>
                  <button> Read More</button>
              </div>
              <div class="box">
                  <i class="fa-solid fa-chart-simple"></i>
                  <h3>Analytics and M&A</h3>
                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi maiores explicabo ipsum non earum? </p>
                  <button> Read More</button>
              </div>
              <div class="box">
                  <i class="fa-solid fa-plane"></i>
                  <h3>Middle Marketing</h3>
                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi maiores explicabo ipsum non earum? </p>
                  <button> Read More</button>
              </div>
              <div class="box">
                  <i class="fa-solid fa-gavel"></i>
                  <h3>Legal Consulting</h3>
                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi maiores explicabo ipsum non earum? </p>
                  <button> Read More</button>
              </div>
              <div class="box">
                  <i class="fa-solid fa-inbox"></i>
                  <h3>Regulatory Risk</h3>
                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi maiores explicabo ipsum non earum? </p>
                  <button> Read More</button>
              </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name:"ServicesComp",

}
</script>

<style lang="scss" scoped>
section{
    width: 100%;
    background-color: black;
    color: white;

    .title-comp{
        padding: 25px;

        .pre-title{
            text-transform: uppercase;
            color: #009ea0;
        }

        h2{
        font-size:60px ;
        margin: 50px 0;

        .special-style{
        display: inline-block;
        background-color:#0e272d ;
        padding: 10px 18px;
        border-radius: 5px;
        
            }
        }



    }
   

    .box{
        width: calc(100% / 3 - 40px);
        margin: 30px 20px;
        background-color: #19191f;
        border-radius: 10px;
        padding: 40px;
        color: white;

               
            i{ 
                font-size: 40px;
                color: #07797a;
                
            }
            p{
                color: gray;
                margin: 25px 0;
            }

            h3{
                margin-top: 30px;
            }
    }

    }

     button{
             padding:  15px;
             
             border-radius: 10px;
             text-transform: uppercase;
             background-color: transparent;
             color: white;
             border: 2px solid #058283
         }

     

</style>