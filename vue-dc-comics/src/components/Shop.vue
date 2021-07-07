<template>
  <div>
      <section>
      <ul>
          <li>
              <a href="#">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="buy-comics-digital-comics">
                 digital comics 
              </a>
         </li>
          <li>
              <a href="#">
                <img src="../assets/img/buy-comics-merchandise.png" alt="comics-merchandise">
                dc merchandise
              </a>
         </li>
          <li>
              <a href="#">
                <!-- <img src="../assets/img/buy-subscriptions.png" alt="buy-subscription"> -->
                <img src="../assets/img/buy-comics-merchandise.png" alt="comics-merchandise">
                subscription
              </a>
         </li>
          <li>
              <a href="#">
                <!-- <img src="../assets/img/buy-shop-locator.png" alt="buy-subscription"> -->
                <img src="../assets/img/buy-comics-merchandise.png" alt="comics-merchandise">
                comic shop locator
              </a>
         </li>
          <li>
              <a href="#">
                <!-- <img src="../assets/img/buy-dc-power-visa.png" alt="buy-dc-power-visa"> -->
                <img src="../assets/img/buy-comics-merchandise.png" alt="comics-merchandise">
                dc power visa
              </a>
         </li>
      </ul>
  </section>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

div{
    background-color: blue;
    section{
    margin: 0 10%;
    padding: 20px 0;
    ul{
        display: flex;
        justify-content: center;
        align-items: center;
        justify-content: space-between;
        li{
            list-style: none;
            display: inline;
            a{
                color: white;
                text-decoration: none;
                text-transform: uppercase;
                img{
                    width: 50px;
                }
            }
        }
    }
}
}

</style>