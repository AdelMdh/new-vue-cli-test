<template>
<div class="navigation">
  <a href="">Digital Davinci Dz</a>
  <nav>
    <router-link to="/">الرئيسية</router-link> 
    <router-link to="/categorie">الفئات</router-link> 
    <router-link to="/about"> معلومات عنا </router-link> 
    <router-link to="/call">اتصل بنا</router-link>
  </nav>
</div>
  <router-view/>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Cairo:wght@300;500;700;800;900&family=Khula:wght@800&display=swap');
</style>

// -- style de navigation bar 
<style lang="scss">
*{
  margin: 0;
  padding: 0;
}
#app {
 font-family: 'Cairo', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
}
.navigation {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  height: 80px;
  background-color: #00051F;

  a{
    cursor: pointer;
    font-weight: 900;
    font-size: 30px;
    color: #ffff;
    margin-left: 30px;
    text-decoration: none;
  }
}


nav {
  padding: 30px;

  

  a {
    font-weight: bold;
    color: #fff;
    text-decoration: none;
    font-size: 30px;
    padding-right: 50px;

    
    &.router-link-exact-active{
    color: #CA4155;

    }
  

  }
}
</style>

