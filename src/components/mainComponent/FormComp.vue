<template>
  <section>
      <div class="container my-5">
          <div class="row">
              <div class="col-8">
                  <div class="row ">
                      <div class="col-12 ">
                          <div class="title-comp">
                            <span class="pre-title">send a message</span>
                            <h2> Get in <span class="special-style">Touch</span> </h2>
                            <div class="d-flex justify-content-between">
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
                            
                        </div>
                    </div>
                      </div>
                      <div class="col-12">
                          <div class="input-container d-flex flex-wrap justify-content-between position-relative">
                              <img src="../../assets/img/image (1).png" alt="">
                              <input class="form-control " placeholder="Name" type="text">
                              <input class="form-control" placeholder="Phone"   type="text">
                              <input class="form-control" placeholder="Email"   type="text">
                              <input class="form-control" placeholder="More Info"   type="text">
                          </div>
                          <textarea class="form-control"  placeholder="Message"  name="" id="" cols="30" rows="10"></textarea>

                      </div>
                  </div>
              </div>
              <div class="col-4 d-flex  flex-column pt-5">
                  <div class="text">
                      <h3>Example Inc.</h3>
                      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. </p>
                       <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. </p>
                  </div>
                  <div class="contact">
                      <ul>
                        <li><i class="fa-solid fa-phone"></i> 1 (305) 1234-5678</li>
                        <li><i class="fa-solid fa-envelope"></i> hello@example.com</li>
                        <li><i class="fa-solid fa-location-dot"></i>  Main Avenue,987</li>
                    </ul>
                    <button> view map</button>
                  </div>
              </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
section{
    width: 100%;
    
    .input-container{
        img{
            position: absolute;
            z-index: 998;
            top: 20%;
            left: 46%;
            
            
        }
        input{
            width: calc(100%/ 2 - 20px);
            margin: 10px ;
            padding: 15px ;
            background-color:#ececec ;
            border: none;

        }
    }
    textarea{
        width:calc( 100% - 20px);
        margin: 10px;
         padding: 15px ;
        background-color:#ececec ;
        border: none;
    }

     .title-comp{
        padding: 15px;
        color: white#21333e;

        .pre-title{
            text-transform: uppercase;
            color: #009ea0;
        }

        h2{
        font-size:60px ;
        margin: 20px 0;

        .special-style{
        display: inline-block;
        background-color:#daeced ;
        color: #058283;
        padding: 10px 18px;
        border-radius: 5px;
        
            }
        }

        p{
            color: gray;
        }



    }

    .text{
        p{
            color: gray;
        }
        margin-bottom: 50px;
    }

    .contact{
        width: 100%;

        
        ul{
            list-style: none;
            padding: 0;
            li{
                padding: 10px 0 ;
            }
            i{
                background-color: #daeced;
                color: #058082;
                padding: 20px;
                margin-right: 10px;
                
                border-radius: 50%;
            }

            
        }

        button{
             padding: 15px 30px;
             border-radius: 10px;
             border: 1px solid #076b6d;
             text-transform: uppercase;
             background-color: transparent;
             
             color:#076b6d;
         }
    }

    
}

</style>