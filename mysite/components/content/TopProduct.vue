<template>
  <div class="top-product">
    <div id="top-product-first">
      <div id="button">
        <LinkButton title="test" link="'top-profile-header'"/>
      </div>
    </div>
    <div id ="top-product-second">
    
    </div>
  </div>
</template>

<style>
#top-product-first {
background-image: url('~static/images/slide04.jpg');
  background-size: cover;
  max-width: 100%;
  height: 50vh;
  position: relative;
}

#top-product-second {
background-image: url('~static/images/slide02.jpg');
  background-size: cover;
  max-width: 100%;
  height: 50vh;
}

#button {
  position : absolute;
  top:50%;
  left:50%;
  margin-right: -50%;
  transform: translate(-50%,-50%);

  border:solid 2px #1f1f1f;
  width: 300px;
  height: 50px;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
</style>
