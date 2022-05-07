<template>
  <div class="home">
    <section>
      <img src="../assets/logo.png" alt="">
      <div class="context">
        <h1>مرحبا بكم!</h1>
        <p>في متجرنا الإلكتروني نوفر لكم <br>
        <span>
          اجمل اللوحات الفنية           
        </span></p>
        <div class="buttons">
      <div class="buttonEndText">
            <div class="button">
        تصفح الفئات
        </div>
        <p class="text4">أفلام، مسلسلات، ألعاب، إنمي...إلخ</p>
      </div>
        <router-link to="/categorie" class="button-mini">معرفة المزيد عنا</router-link>
        </div>
        <div class="reseaux">
           <a href="https://www.facebook.com/DigitalDaVinciDz" target="_blank" rel="noopener noreferrer"><i class="fa-brands fa-facebook-f"></i></a>
           <a href="https://www.instagram.com/digital_davinci_dz/" target="_blank" rel="noopener noreferrer"><i class="fa-brands fa-instagram"></i></a>
        </div>
      </div>
     
    </section>
  </div>
</template>

<style scoped>
section {
  background-color: #00051F;
  width: 100vw;
  height: 90vh;
  display: flex;
  justify-content: space-between;
  padding-top: 500px, 50px;
}
section img{
  height: 60%;
  width: auto;
  filter: invert(100%);
  margin: 50px;
}
.context{
  margin: 50px;
  width: 700px;
  height: 400px;
  border-radius: 8px;
  padding-top: 10px;
}

.context h1, p{
  font-size: 40px;
}
.context p span {
  font-size: 60px;
}
.buttons{
  display: flex;
  flex-direction: row-reverse ;
  width: 100%;
  height: auto;
  justify-content: center;
  align-items: center;
  margin-top: 20px;

}
.button {
  margin-left: 50px;
  font-size: 30px;
  background-color: #CA4155;
  padding: 15px 60px;
  border-radius: 10px;
  cursor: pointer;
  transition: 0.3s ease;
}
.text4{
  font-size: 18px;
  align-items: center;
  width: 280px;
  margin: 10px 0 0 46px;

}
.buttonEndText{
justify-content: center;
}
.button:hover{
  background-color: #bb3246;
}
.button-mini {
  color: #fff;
  text-decoration: none;
  font-size: 24px;
  transition: 0.3s ease;
}
.button-mini:hover{
  color: #CA4155;
}
.reseaux{
  margin-top: 30px;
}
.reseaux a{
  margin-right: 50px;
  font-size: 50px;
  color: #fff;
  transition: 0.3s ease;
}
.reseaux a:hover{
  color: #bb3246;
}

</style>

