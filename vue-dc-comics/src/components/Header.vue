<template>
  <header>
      <a href="#">
          <img src="../assets/img/dc-logo.png" alt="dc logo">
      </a>
      <nav>
          <ul>
              <li><a href="#">characters</a></li>
              <li><a href="#">comics</a></li>
              <li><a href="#">movies</a></li>
              <li><a href="#">tv</a></li>
              <li><a href="#">games</a></li>
              <li><a href="#">collectibles</a></li>
              <li><a href="#">videos</a></li>
              <li><a href="#">fans</a></li>
              <li><a href="#">news</a></li>
              <li><a href="#">shop</a></li>
          </ul>
      </nav>
  </header>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

header{
    margin: 0 10%;
    padding-top: 10px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 100px;
    a{

    }
    ul{
        li{
            list-style: none;
            display: inline;
            margin: 0 10px;
            font-size: 15px;
            
            a{
                text-decoration: none;
                text-transform: uppercase;
                color: #000;
                padding: 40px 0;
                &:hover{
                    border-bottom: 3px solid blue;
                    color: blue;
                }
            }
        }
    }
}

</style>