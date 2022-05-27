<template>
  <section>
      <div class="container d-flex justify-content-between  ">
          <div class="box ">
              <span><i class="fa-solid fa-users"></i></span>
              <h2>Human Capital</h2>
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ea eaque assumenda labore delectus dolores doloribus error iusto non quas, aperiam quaerat maiores ratione dolore libero officiis alias excepturi, sapiente iste.</p>
          </div>
          <div class="box ">
              <span></span>
              <h2>Human Capital</h2>
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ea eaque assumenda labore delectus dolores doloribus error iusto non quas, aperiam quaerat maiores ratione dolore libero officiis alias excepturi, sapiente iste.</p>
          </div>
          <div class="box ">
              <span></span>
              <h2>Human Capital</h2>
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ea eaque assumenda labore delectus dolores doloribus error iusto non quas, aperiam quaerat maiores ratione dolore libero officiis alias excepturi, sapiente iste.</p>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name:"WhiteCard",

}
</script>

<style lang="scss" scoped>

section{
    width: 100%;
    height: 600px;
    background-color:#eef4ed ;
    display: flex;
    justify-content: center;
    align-items: center;

    .box{
        width: calc(100% / 3);
        background-color: white;
        border-radius: 10px;
        padding: 15px;
        margin: 0 20px;

        span{
            display: flex;
            justify-content: center;
            align-items: center;
            width: 100px;
            height: 100px;
            border-radius: 50%;
            background-color: #daeced;
            margin-bottom: 20px;
            i{
                font-size: 40px;
                color: #148b93;
            }
        }

    }
}
</style>