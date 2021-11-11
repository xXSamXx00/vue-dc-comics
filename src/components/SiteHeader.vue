<template>
  <div class="container">
    <header id="site_header">
      <div class="logo">
        <img src="../assets/dc-logo.png" alt="Logo DC">
      </div>
      <nav class="main_menu">
        <ul>
          <li><a href="#">Characters</a></li>
          <li><a href="#">Comics</a></li>
          <li><a href="#">Movies</a></li>
          <li><a href="#">Tv</a></li>
          <li><a href="#">Games</a></li>
          <li><a href="#">Collectibles</a></li>
          <li><a href="#">Videos</a></li>
          <li><a href="#">Fans</a></li>
          <li><a href="#">News</a></li>
          <li><a href="#">Shop</a></li>
        </ul>
      </nav>
    </header>
  </div>
</template>

<script>
export default {

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#site_header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 140px;
  img {
    width: 90%;
  }
  .main_menu {
    height: 100%;
    ul {
      list-style: none;
      height: 100%;
      li {
        display: inline-block;
        margin-left: 30px;
        height: 100%;
        a {
          display: inline-block;
          line-height: 140px;
          text-decoration: none;
          text-transform: uppercase;
          font-weight: 800;
          font-size: 13px;
          color: #464646;
          &:hover {
            color: #0282F9;
            border-bottom: 5px solid #0282F9;
          }
        }
      }
    }
  }
}
</style>