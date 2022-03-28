<template>
  <body>
    <div class="navbar-div md:inline-flex mt-10">
      <div class="items-center">
        <a class="b-logo" href="#">
          <img src="../../../../../bank-monie/src/components/main/image/b-logo.png" alt="">
        </a>
        <a class="monie" href="#"><p>ank<span class="text-blue-500">monie</span></p></a>
      </div>

      <div class="link-nav">
        <a href="#"><span class="home text-blue-500">Home</span></a>
        <a class="other-nav" href="#">About Us</a>
        <a class="other-nav" href="#">Services</a>
        <a class="other-nav" href="#">FAQs</a>
      </div>

      <div>
        <button class="btn btn-blue">Log in</button>
      </div>

      <div class="oauth absolute">
        <button class="btn-get-started btn-blue">Get POS Terminal</button>
      </div>

      <div class="over-head-image absolute">
        <img src="../../../../../bank-monie/src/components/main/image/circle.png"/>
      </div>

      <div class="holder absolute"></div>
      <div class="holder1 absolute"></div>
      <div class="holder2 absolute"></div>

      <div class="what-we-do absolute">
        <p>At bankmonie we provide financial services in your</p>
        <p>local community and make money while at it.</p>
      </div>

      <div class="services-navbar mr-64">
        <h1>Providing <span class="text-blue-400">Affordable</span></h1>
       <h1>Financial Services.</h1>
      </div>

      <div class="man-image">
        <img src="../../../../../bank-monie/src/components/main/image/manSmile.png" alt=""/>
      </div>
    </div>

    <div class="second-section mt-64 bg-white ">

      <div class="w-full relative">
        <h1 class=" absolute header">Upgrade your <span class="text-blue-700">Business</span></h1>
        <p class=" absolute next-line">& <span class="text-green-500">earn</span> more with us.</p>
      </div>

      <div class="left-paragraph absolute ml-64 mt-64">
        <img class="bank-image" src="../../../../../bank-monie/src/components/main/image/bankMonie.png" alt=""/>
        <img class="absolute green-image" src="../../../../../bank-monie/src/components/main/image/green-box.png" alt=""/>
      </div>

      <div class="right-paragraph ml-64 mt-64">
        <img src="../../../../../bank-monie/src/components/main/image/leftimage.png" alt=""/>
      </div>

      <div class="three-images">
        <img class="move-center-image" src="../../../../../bank-monie/src/components/main/image/two-women.png" alt="">
        <img src="../../../../../bank-monie/src/components/main/image/pos-image.png" alt=""/>
      </div>
    </div>

  </body>
</template>

<script>
export default {
  name: "LandingPage",
}

</script>

<style>
@import "../style/Page.css";
</style>