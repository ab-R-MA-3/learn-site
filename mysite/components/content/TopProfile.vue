<template>
  <div class="top-profile">
    <div class="top-profile-content">
      <div id="top-profile-header">
          <h1>Profile</h1>
      </div>
      <div id="top-profile-message">
        <p>
          　私たちは、北海道を拠点に活動するプログラマー集団です。
          北の大地から全国へ、業務の自動化・効率化を支援する技術を開発し、
          日本の経済成長に貢献します。
        </p>
        <br>
        <p>
          　私たちは以下の技術を得意としています。
          システム・ツールの開発についてお悩みがございましたら、
          些細な内容でも構いませんので、一度ご相談ください。
        </p>
        <br>
        <br>
        <p>【言語】</p>
        <p>
            Java
            <br>
            PHP
            <br>
            Python
            <br>
            go
        </p>
      </div>
    </div>
  </div>
</template>

<style>
.top-profile {
  animation: 1.5s profile-kan;
  max-width: 100%;
  height: 100%;
  margin-top: 40px;
  margin-bottom: 40px;
}

.top-profile-content {
  top: 100px;
  width: 700px;
  margin-top: 20px;
  margin-left: auto;
  margin-right: auto;
}

#top-profile-header {
  margin-top:20px;
  margin-bottom: 20px;
  border-bottom: solid 2px #000000;
}

#top-profile-message {
  margin-top: 10px;
  margin-bottom: 10px;
}

@keyframes profile-kan {
  
  0% {
    transform: translate(100%,0%);
    opacity: 0;
  }

  100% {
    transform: translate(0%,0%);
    opacity: 1;
  }
}
</style>
