<template>
  <div class="aboutme">
    <h2>About me</h2>
    <p>東京でWebエンジニアをしています。最近はテキストエディタのプラグイン開発とかをやります。来世は木か石になりたいです</p>
    <div class="skills">
      <h2>Skills</h2>
      <div class="good">
        <h3>👍ﾜﾀｼﾁｮｯﾄﾃﾞｷﾙ</h3>
        <span class="tag">JavaScript</span>
        <span class="tag">Riot.js</span>
        <span class="tag">Vue.js</span>
        <span class="tag">Express</span>
        <span class="tag">Electron</span>
        <span class="tag">Python</span>
        <span class="tag">Flask</span>
        <span class="tag">Ruby</span>
        <span class="tag">Ruby on Rails</span>
        <span class="tag">Itamae</span>
      </div>
      <div class="curios">
        <h3>👀興味がある</h3>
        <span class="tag">Haskell</span>
        <span class="tag">Scala</span>
        <span class="tag">TypeScript</span>
        <span class="tag">React</span>
        <span class="tag">Docker</span>
        <span class="tag">CSS</span>
      </div>
    </div>
  </div>
</template>
<style scoped>
.aboutme {
  padding-top: 2em;
  padding-bottom: 4em;
  background-color: #006691;
  color: #CDCBA6;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-flow: column;
}
.skills {

}

.skills .good{
  margin-bottom: 1.5em;
}

.skills .curios{
  margin-bottom: 1.5em;
}

.skills h2 {
}

.tag {
  background-color: #52B3D9;
  border-radius: 5px;
  padding: 0.25em;
  color: #2C3E50;
  justify-content: flex-start;
}
</style>
