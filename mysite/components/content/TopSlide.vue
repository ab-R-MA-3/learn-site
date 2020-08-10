<template>
  <div class="top">
    <div class="top-header">
      <div id="top-logo">
        <h1>RedStar Systems</h1>
      </div>
      <div id="top-nav">
        <div id="top-nav-li"><a href="#top-profile"><h2>Profile</h2></a></div>
        <div id="top-nav-li"><a href="#top-product"><h2>Product</h2></a></div>
        <div id="top-nav-li"><a href="#top-blog"><h2>blog</h2></a></div>
      </div>
    </div>
    <div class="top-slide">
      <h1>次世代のパフォーマンスを 日本へ</h1>
    </div>
  </div>
</template>

<style>
.top {
  /*背景*/
  background-image: url('~static/images/slide05.jpg');
  background-size: cover;
}

.top-header {
  display: flex;
  justify-content: space-between;
  background-color: #f1f1f1;
}

.top-slide {
  max-width: 100%;
  height: 100vh;
  position: relative
}

.top-slide h1 {
    position: absolute;
    top: 43%;
    left: 50%;
    margin-right: -50%;
    transform: translate(-50%, -50%);

    color: #f1f1f1;
    font-size: 1cm;
    animation-name: ph;
    animation-duration: 5000ms;
  }

#top-logo h1{
  color: #FF0000;
  margin-left: 10px;
  margin-top: 10px;
  margin-bottom: 3px;
}

#top-nav {
  display: flex;
  justify-content: center;
}

#top-nav a {
  color: #FF0000;
  text-decoration: none;
}

#top-nav h2 {
  margin: 30px;
  margin-top: 15px;
  margin-bottom: 0px;
}

@keyframes appear {
  /*
  0% {
    transform: translate(-100%, -10%);
  }

  25% {
    transform: translate(-90%, -20%);
  }

  50% {
    transform: translate(-80%, -30%);
  }

  75% {
    transform: translate(-70%, -40%);
  }

  100% {
    transform: translate(-50%, -50%);
  }
  */
}
</style>
