<template>
<section>
    <!-- Parte con i link -->
      <div>
      <ul>
          <li class="bold">abc</li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li class="bold">abc</li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
      </ul>
      <ul>
          <li class="bold">abc</li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
      </ul>
      <ul>
          <li class="bold">abc</li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
          <li><a href="#">abc</a></li>
      </ul>

      <img src="../assets/img/dc-logo-bg.png" alt="">
  </div>

  <!-- Parte con i social -->
  <main>
      <button>SIGN-UP NOW!</button>

      <section class="social">
          <a href="#">FOLLOW US</a>
          <a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a>
          <a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a>
          <a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a>
          <a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a>
          <a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a>
      </section>
  </main>
</section>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

section{
    background-image: url(../assets/img/footer-bg.jpg);
    div{
        margin: 0 10%;
    display: flex;
    ul{
        padding: 25px;
        li{
            
            a{
                color: white;
                text-decoration: none;
                
            }
        }
    }
    img{
        margin-left: 30%;
        height: 350px;
        position: relative;
    }
}

main{
    background-color: gray;
    margin: 0 10%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    button{
        border-radius: 0;
        background-color: gray;
        border: 2px solid blue;
        color: white;
        padding: 5px;
    }

    .social{
        a{
            color: white;
            text-decoration: none;
            padding: 5px;
        }
    }
}

}

</style>