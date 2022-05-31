<template>
  <section>
      <div class="container ">
          <div class="row ">
              <div class="col-12 d-flex justify-content-center">
                        <div class="title-comp text-center pt-5">
                            <span class="pre-title">our business areas</span>
                            <h2><span class="special-style">Pricing</span> Table </h2>
                            <div class="d-flex justify-content-between">
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta dolore ducimus omnis repudiandae</p>
                  
                        </div>
                </div>
            </div>
              <div class="col-12 d-flex mb-5">
                  <div class="box">
                      <div class="title-box">
                          <i class="fa-solid fa-globe"></i>
                            <h3>Standard</h3>
                            <h2>$ 490/mo</h2>
                      </div>
                      <div class="list-container d-flex justify-content-around">
                          <ul>
                          <li>Standard Accounting</li>
                          <li> Platform Access</li>
                          <li>Business Orientation</li>
                          <li>Dedicated Consultant</li>
                          <li>Personal Assistance</li>
                      </ul>
                      <ul>
                          <li><i class="fa-solid fa-check"></i></li>
                          <li><i class="fa-solid fa-check"></i></li>
                          <li><i class="fa-solid fa-x"></i></li>
                          <li><i class="fa-solid fa-x"></i></li>
                          <li><i class="fa-solid fa-x"></i></li>
                      </ul>
                      </div>
                    </div>
                    <div class="box position-relative box-professional">
                        <span class="popular"> Most <br> Popular </span>
                      <div class="title-box">
                          <i class="fa-solid fa-briefcase"></i>
                            <h3>Professional</h3>
                            <h2>$ 890/mo</h2>
                      </div>
                      <div class="list-container d-flex justify-content-around">
                          <ul>
                          <li>Standard Accounting</li>
                          <li> Platform Access</li>
                          <li>Business Orientation</li>
                          <li>Dedicated Consultant</li>
                          <li>Personal Assistance</li>
                      </ul>
                      <ul>
                          <li><i class="fa-solid fa-check"></i></li>
                          <li><i class="fa-solid fa-check"></i></li>
                          <li><i class="fa-solid fa-check"></i></li>
                          <li><i class="fa-solid fa-x"></i></li>
                          <li><i class="fa-solid fa-x"></i></li>
                      </ul>
                      </div>
                    </div>   
                    <div class="box">
                      <div class="title-box">
                          <i class="fa-solid fa-gem"></i>
                            <h3>Ultimate</h3>
                            <h2>$ 1.390/mo</h2>
                      </div>
                      <div class="list-container d-flex justify-content-around">
                          <ul>
                          <li>Standard Accounting</li>
                          <li> Platform Access</li>
                          <li>Business Orientation</li>
                          <li>Dedicated Consultant</li>
                          <li>Personal Assistance</li>
                      </ul>
                      <ul>
                          <li><i class="fa-solid fa-check"></i></li>
                          <li><i class="fa-solid fa-check"></i></li>
                          <li><i class="fa-solid fa-check"></i></li>
                          <li><i class="fa-solid fa-check"></i></li>
                          <li><i class="fa-solid fa-check"></i></li>
                      </ul>
                      </div>
                    </div> 
                      
                  
              </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name:"PricingComp",

}
</script >

<style lang="scss" scoped>
section{
    width: 100%;
    
    background-color: #eef4ed;

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
        background-color:#cce3de ;
        color: #007d86;
        padding: 10px 18px;
        border-radius: 5px;
        
            }
        }

        p{
            color: gray;
        }



    }
    .box-professional{
            transform: scale(1.1);
        }

     .box{
        width: calc(100% / 3 - 40px);
        margin: 30px 20px;
        background-color: white;
        border-radius: 10px;
        padding: 40px 10px;
        color: #058283;

        


        .popular{
            position: absolute;
            left: 0;
            display: inline-block;
            background-color: #058283;
            padding: 5px 10px ;
            border-radius: 0 20px 20px 0;
            color: white;
            font-size: 12px;
        }

            .title-box{
                text-align: center;
                margin-bottom: 25px;
            }
        

               
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
                color: black;
                font-weight: bold;
            }
            h2{
                font-weight: bold;
                margin: 20px 0;
            }

            ul{
                list-style: none;
                li{
                    padding: 10px 0;
                    color: gray;
                    i{
                font-size:15px;
            }
                }
            }

            i{
                font-size:40px;
            }
    }
}

</style>