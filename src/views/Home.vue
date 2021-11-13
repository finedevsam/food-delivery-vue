<template>
<div class="topbar">
  <div class="header">
    <div class="logo">
      <img src="../assets/logo.svg" alt="Logo" class="logo-img" />
    </div>
    <div class="menu">
      <ul>
        <a>Home</a>
        <a>Product</a>
        <a>Faq</a>
        <a>Contact</a>
      </ul>
  </div>
  </div>
  <div class="banner">
    <img src="../assets/banner.svg" alt="banner" />
    <div class="title">Food App</div>
    <div class="desc"><p>Why stay hungry when you can order form Bella Onojie</p></div>
    <div class="download-text"><p>Download the bella onoje’s food app now on</p></div>
    <div class="playstore">
      <div class="button-appstore">Appstore</div>
      <div class="button-playstore">Playstore</div>
    </div>
    <div class="mobile">
      <div class="mobile-colored">
        <img src="../assets/m1.svg" alt="m1" />
      </div>
      <div class="mobile-not-colored">
        <img src="../assets/m2.svg" alt="m2" />
      </div>
    </div>
  </div>
  
</div>
<div class="hr"></div>

<div class="how-app-work">
  <div class="app-title">
    <p>How the app works</p>
  </div>
  <div class="account-block">
    <div class="account-mobile">
      <img src="../assets/m3.svg" alt="m3" />
      <div class="text-box">
        <h6 class="acct-title">Create an account</h6>
      </div>
      <div class="create-login">Create/login to an existing account to get started</div>
      <p class="sub-title">An account is created with your email and a desired password</p>
      
    </div>
  </div>
</div>
<section class="explore">
  <div class="explore-title">
    <h3>Explore varieties</h3>
  </div>
  <div class="explore-title-2">
    <h3>Shop for your favorites meal as e dey hot.</h3>
  </div>
  <div class="explore-title-3">
    <h4>Shop for your favorite meals or drinks and enjoy while doing it.</h4>
  </div>
  <div class="explore-image">
    <img src="../assets/m4.svg" alt="m4" />
  </div>
</section>
<section class="checkout">
  <div class="checkout-image">
    <img src="../assets/m5.svg" alt="m5" />
  </div>
  <div class="checkout-title">
    <h3>Checkout</h3>
  </div>
  <div class="checkout-title-2">
    <h2>When you done check out and get it delivered.</h2>
  </div>
  <div class="checkout-title-3">
    <h4>When you done check out and get it delivered with ease.</h4>
  </div>
</section>
<section class="foot">
  <div class="foot-image">
    <img src="../assets/m6.svg" alt="m6" />
    <div class="foot-title">
      <h2>Download the app now.</h2>
    </div>
    <div class="foot-title-1">
      <h4>Available on your favorite store. Start your premium experience now</h4>
    </div>
    <div class="foot-button">
      <div class="foot-button-appstore">Appstore</div>
      <div class="foot-button-playstore">Playstore</div>
    </div>
  </div>
</section>
<section class="footer">
  <div class="footer-logo">
    <img src="../assets/logo.svg" alt="Footer-Logo" />
  </div>
</section>
</template>

<script>
// @ is an alias to /src

</script>

<style scoped>
.topbar{
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding: 0px;

  position: absolute;
  width: 1440px;
  height: 830px;
  left: 0px;
  top: 1px;
  background: #FFFFFF;
  
}
.header{
    position: relative;
    
  }
  
  .menu{
    margin-inline: 300%;
  }
  .menu a{
    position: static;
    left: 14.08%;
    right: 14.08%;
    top: 20.83%;
    bottom: 20.83%;
    

    /* Link */

    font-family: Montserrat;
    font-style: normal;
    font-weight: 600;
    font-size: 16px;
    line-height: 28px;
    /* identical to box height, or 175% */

    text-align: center;
    letter-spacing: 0.2px;

    color: #FA4A0C;


    /* Inside Auto Layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 10px;

  }
  
  .logo {
    position: absolute;
    left: 8.13%;
    right: 8.13%;
    top: 0%;
    bottom: 0%;

    /* background: url(.png); */
  }
  .banner{
    position: relative;
    margin: 0px;
    margin-top: 3%;
    /* color: #F7F7F7; */
  }
  .banner-img{
    /* position: absolute; */
    width: 1440px;
    height: 619px;
    left: 0px;
    top: -1px;

    background: linear-gradient(0deg, rgba(23, 16, 16, 0.6), rgba(23, 16, 16, 0.6));
  }

  .title {
    position: absolute;
    line-height: 36px;
    top: 10%;
    left: 44.08%;
    right: 44.08%;
    bottom: 88.96%;

    font-family: Montserrat;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    text-align: center;
    letter-spacing: 0.1px;

    color: #F7F7F7;
  }

  .desc {
    position: absolute;
    left: 3.38%;
    right: 3.38%;
    top: 15%;
    bottom: 5.56%;

    font-family: Poppins;
    font-style: normal;
    font-weight: bold;
    font-size: 58px;
    line-height: 80px;
    /* or 138% */

    text-align: center;
    letter-spacing: 0.2px;

    color: #FFFFFF;
  }

  .download-text{
    position: absolute;
    left: 12.23%;
    right: 12.09%;
    top: 50%;
    bottom: 50%;

    /* H4 */

    font-family: Montserrat;
    font-style: normal;
    font-weight: 500;
    font-size: 24px;
    line-height: 38px;
    /* identical to box height, or 158% */

    text-align: center;
    letter-spacing: 0.2px;

    color: #F7F7F7;

  }

  .playstore{
    
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-gap: 20px;
    position: absolute;
    left: 37%;
    right: 37%;
    top: 65%;
    bottom: 50%;
  }
  .button-appstore{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 16px 0px;

    position: static;
    left: 0%;
    right: 0%;
    top: 0%;
    bottom: 0%;

    font-family: Montserrat;
    font-style: normal;
    font-weight: 50;
    font-size: 20px;
    line-height: 20px;

    background: #FA4A0C;
    box-shadow: 0px 10px 30px rgba(183, 50, 39, 0.2);
    border-radius: 30px;

    /* Inside Auto Layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 0px;
    color: #F7F7F7;
  }
  .button-playstore{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 16px 0px;

    position: static;
    left: 0%;
    right: 0%;
    top: 0%;
    bottom: 0%;
    font-family: Montserrat;
    font-style: normal;
    font-weight: 50;
    font-size: 20px;
    line-height: 20px;

    /* background:0ex; */
    box-shadow: 0px 10px 30px rgba(226, 233, 231, 0.747);
    border-radius: 30px;
    border-style: solid;
    

    /* Inside Auto Layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 0px;
    color: #F7F7F7;
  }
  .mobile{
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-gap: 20px;
    position: absolute;
    
  }
  .mobile-colored{
    position: absolute;
    width: 299px;
    height: 586px;
    left: 350px;
    top: -300px;

    /* background: url(.png); */

    filter: drop-shadow(50px 30px 150px rgba(46, 4, 4, 0.21));

  }
  .mobile-not-colored{
    position: absolute;
    width: 285px;
    height: 531px;
    left: 716px;
    top: -70px;

  }

  .hr{
    position: absolute;
    width: 884px;
    height: 0px;
    left: 278px;
    top: 1378.91px;

    border: 3px solid #E4E4E4;
  }
  .how-app-work{
    position: absolute;
    bottom: 800px;
  }
  .app-title{
    position: absolute;
    width: 425px;
    height: 36px;
    left: 495px;
    top: 1451px;

    font-family: Poppins;
    font-style: normal;
    font-weight: 600;
    font-size: 44px;
    line-height: 36px;
    /* identical to box height, or 82% */

    letter-spacing: 0.1px;

    color: #000000;

    opacity: 0.8;
  }

  .account-block{
    position: absolute;
    width: 1400px;
    height: 806.99px;
    left: 0px;
    top: 1530px;

    background: #FFFFFF;
  }
  .account-mobile{
    position: absolute;
    width: 302px;
    height: 525px;
    left: 245px;
    top: 78px;

    /* background: url(.png); */
    filter: drop-shadow(50px 30px 150px rgba(46, 4, 4, 0.15));
  }
  .acct-title{
    position: static;
    left: 0%;
    right: 0%;
    top: 0%;
    bottom: 0%;

    /* H3 */

    font-family: Montserrat;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 20px;
    /* identical to box height, or 150% */

    letter-spacing: 0.1px;

    color: #FA4A0C;


    /* Inside Auto Layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 0px;
  }
  .text-box{
    position: absolute;
    /* size: 100%; */
    /* float: right; */
    /* left: 150%; */
    top: 60%;
    right: -150%;
  }
  .create-login{
    position: absolute;
    left: 150%;
    right: -250%;
    top: 67%;
    /* bottom: -1000%; */

    /* H2 */

    font-family: Montserrat;
    font-style: normal;
    font-weight: bold;
    font-size: 40px;
    line-height: 57px;
    /* or 142% */

    letter-spacing: 0.2px;

    /* text */

    color: #252B42;


    /* Inside Auto Layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 10px;
  }
  .sub-title{
    position: absolute;
    left: 150%;
    right: -200%;
    top: 90%;
    bottom: 10.42%;

    /* H4 */

    font-family: Montserrat;
    font-style: normal;
    font-weight: 500;
    font-size: 24px;
    line-height: 30px;
    /* or 158% */

    letter-spacing: 0.2px;

    /* second text */

    color: #737373;


    /* Inside Auto Layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 10px;
  }
  .explore{
    position: absolute;
    width: 1400px;
    height: 806.99px;
    left: 0px;
    top: 2202px;

    background: #FFFFFF;
  }
  .explore-title{
    position: absolute;
    left: 20%;
    right: 30%;
    top: 40%;
    bottom: 0%;

    /* H3 */

    font-family: Montserrat;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 36px;
    /* identical to box height, or 150% */

    letter-spacing: 0.1px;

    color: #FA4A0C;


    /* Inside Auto Layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 0px;
  }
  .explore-title-2{
    position: absolute;
    left: 13%;
    right: 50%;
    top: 45%;
    bottom: 7.46%;

    /* H2 */

    font-family: Montserrat;
    font-style: normal;
    font-weight: bold;
    font-size: 30px;
    line-height: 50px;
    /* or 142% */

    letter-spacing: 0.2px;

    /* text */

    color: #252B42;


    /* Inside Auto Layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 10px;
  }
  .explore-title-3{
    position: absolute;
    left: 13%;
    right: 50%;
    top: 65%;
    bottom: 10%;

    /* H4 */

    font-family: Montserrat;
    font-style: normal;
    font-weight: 500;
    font-size: 24px;
    line-height: 38px;
    /* or 158% */

    letter-spacing: 0.2px;

    /* second text */

    color: #737373;


    /* Inside Auto Layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 10px;
  }
  .explore-image{
    position: absolute;
    width: 200px;
    height: 500px;
    left: 750px;
    top: 78px;

    /* background: url(.png); */
    filter: drop-shadow(50px 30px 150px rgba(46, 4, 4, 0.15));

  }
  .checkout{
    position: absolute;
    width: 1440px;
    height: 806.99px;
    left: 0px;
    top: 2935px;

    background: #FFFFFF;
  }
  .checkout-image{
    position: absolute;
    width: 278px;
    height: 511px;
    left: 245px;
    top: 81px;

    /* background: url(.png); */
    filter: drop-shadow(50px 30px 150px rgba(46, 4, 4, 0.15));
  }
  .checkout-title{
    position: absolute;
    left: 65%;
    right: 0%;
    top: 43%;
    bottom: 0%;

    /* H3 */

    font-family: Montserrat;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 36px;
    /* identical to box height, or 150% */

    letter-spacing: 0.1px;

    color: #FA4A0C;


    /* Inside Auto Layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 0px;
  }
  .checkout-title-2{
    position: absolute;
    left: 50%;
    right: 2%;
    top: 50%;
    bottom: 0%;

    /* H2 */

    font-family: Montserrat;
    font-style: normal;
    font-weight: bold;
    font-size: 25px;
    line-height: 50px;
    /* or 142% */

    letter-spacing: 0.2px;

    /* text */

    color: #252B42;


    /* Inside Auto Layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 10px;
  }
  .checkout-title-3{
    position: absolute;
    left: 50%;
    right: 0%;
    top: 65%;
    bottom: 10.42%;

    /* H4 */

    font-family: Montserrat;
    font-style: normal;
    font-weight: 500;
    font-size: 24px;
    line-height: 38px;
    /* or 158% */

    letter-spacing: 0.2px;

    /* second text */

    color: #737373;


    /* Inside Auto Layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 10px;
  }
  .foot {
    position: absolute;
    /* height: 100%;
    margin: 0px; */
  }
  .foot-image{
    position: relative;
    width: 130px;
    height: 500px;
    left: -6.4%;
    top: 3750px;

    background: linear-gradient(0deg, rgba(37, 43, 66, 0.4), rgba(37, 43, 66, 0.4));
  }
  .foot-title{
    position: absolute;
    left: 400%;
    right: -700%;
    top: 25%;
    bottom: 12.99%;

    /* H2 */

    font-family: Montserrat;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 57px;
    /* identical to box height, or 142% */

    text-align: center;
    letter-spacing: 0.2px;

    /* Light text */

    color: #FFFFFF;


    /* Inside Auto Layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 10px;
  }
  .foot-title-1{
    position: absolute;
    left: -1.6%;
    right: -1120%;
    top: 35%;
    bottom: 17.24%;

    /* H4 */

    font-family: Montserrat;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 25px;
    /* identical to box height, or 158% */

    text-align: center;
    letter-spacing: 0.2px;

    color: #FFFFFF;


    /* Inside Auto Layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 10px;
  }
  .foot-button{
    
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-gap: 20px;
    position: absolute;
    left: 470%;
    right: -40%;
    top: 65%;
    bottom: 50%;
  }
  .foot-button-appstore{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 18px 31px;

    position: static;
    width: 50px;
    height: 20px;
    left: 0px;
    top: 0px;
    color: #F7F7F7;

    background: #FA4A0C;
    border-radius: 10px;

    /* Inside Auto Layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 16px;
  }
  .foot-button-playstore{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 18px 31px;

    position: static;
    width: 50px;
    height: 20px;
    left: 0px;
    top: 0px;
    color: #F7F7F7;

    /* background: #FA4A0C; */
    border-radius: 10px;
    border-style: solid;

    /* Inside Auto Layout */

    flex: none;
    order: 0;
    flex-grow: 0;
    margin: 0px 16px;
  }
  .footer{
    position: absolute;
    width: 1210px;
    height: 133px;
    left: 115px;
    top: 4270px;


    background: #FFFFFF;
  }
  .footer-logo{
    position: absolute;
    width: 246px;
    height: 102px;
    left: -20.5px;
    top: 2px;

    /* background: url(.png); */
  }
</style>
