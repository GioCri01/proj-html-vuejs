<template>
  <section>
      <div class="container-fluid">
          <div class="row">
              <div class="col-4 offset-2  d-flex justify-content-center align-items-center">
                  <div class="about-container my-5">
                      <span class="pre-title">about the network</span>
                      <h2><span class="special-style">The</span> Company</h2>
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam, enim! Nihil, inventore amet harum nobis laboriosam, repellendus doloremque animi repudiandae veritatis nesciunt explicabo tenetur pariatur? Expedita iure obcaecati dolorum magnam.</p>
                      <div class="container-box d-flex flex-wrap pt-5 ">
                          <div class="box">
                              <h3> <i class="fa-solid fa-award"></i>  tradition</h3>
                              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis dolorum quia sint nisi excepturi.</p>
                          </div>
                          <div class="box">
                              <h3><i class="fa-solid fa-lock"></i> Security</h3>
                              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis dolorum quia sint nisi excepturi.</p>
                          </div>
                          <div class="box">
                              <h3> <i class="fa-solid fa-pen-to-square"></i> tradition</h3>
                              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis dolorum quia sint nisi excepturi.</p>
                          </div>
                          <div class="box">
                              <h3><i class="fa-solid fa-graduation-cap"></i> Expertise</h3>
                              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis dolorum quia sint nisi excepturi.</p>
                          </div>
                      </div>

                      
                  </div>
              </div>
              <div class="col-6 img-box">
                  
              </div>
              
          </div>
      </div>
      
  </section>
</template>

<script>
export default {
name: "CompanyCard"
}
</script>

<style lang="scss" scoped>
section{
    width: 100%;
    

    img{
        width: 100%;
        
    }

    .box{
        width: calc(100% /2 - 20px);
        height: 100%;
        margin: 10px;
        
    }

    .pre-title{
        text-transform: uppercase;
        color: #009ea0;
        
    }

    h2{
        font-size:60px ;
        margin: 50px 0;
    }
    p{
        color: gray;
    }

    .special-style{
        display: inline-block;
        background-color:#daeced ;
        padding: 10px 18px;
        border-radius: 5px;
        color: #058283 ;
    }
    i{
        padding-right: 5px;
        color: #228a8a;
        margin-bottom: 20px;
    }

    .img-box{
        background-image: url(../../assets/img/about-3.jpg);
        background-size: cover;
        background-position: center;
    }
}

</style>