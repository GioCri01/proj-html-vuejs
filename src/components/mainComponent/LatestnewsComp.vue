<template>
  <section>
      <div class="container">
          <div class="row">
              <div class="col-12">
                 <div class="title-comp">
                    <span class="pre-title">our editorial Content</span>
                    <h2>Latest <span class="special-style">News</span></h2>
                    <div class="d-flex justify-content-between">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta dolore ducimus omnis repudiandae</p>
                    <button>see all</button>
              </div>
          </div>             
              </div>
              <div class="col-12 d-flex">
                  <div class="box">
                      <img  src="../../assets/img/news-1.jpg" alt="news1">
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
                      
                  </div>
                  <div class="box">
                      <img src="../../assets/img/news-2.jpg" alt="news2">
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
                      
                  </div>
                  <div class="box">
                      <img src="../../assets/img/news-3.jpg" alt="news3">
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
                      
                  </div>
              </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name:"LatestnewsComp",

}
</script>

<style lang="scss" scoped>
section{
    width: 100%;

     .title-comp{
        padding: 25px;

        .pre-title{
            text-transform: uppercase;
            color: #009ea0;
        }

         p{
             color: gray;
         }

        h2{
        font-size:60px ;
        margin: 50px 0;

        .special-style{
        display: inline-block;
        background-color:#daeced ;
        color: #058283;
        padding: 10px 18px;
        border-radius: 5px;
        
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

    .box{
        width: calc(100% / 3 - 40px);
        margin: 30px 20px;
        background-color: white;
        border-radius: 10px;
        padding: 40px 10px;
        color: #058283;
        position: relative;
        
        img{
            width: 100%;
            filter: brightness(0.5);
            border-radius: 10px;
            
        }

        p{
            position: absolute;
            bottom: 20%;
            left: 10%;
            color: white;
            font-weight: bold;
            font-size: 20px;
        }
        
        }
}

</style>