<template>
  <div class="aboutme">
    <h2>About me</h2>
    <p>東京でWebエンジニアをしています。最近はRSSリーダーとかを作っています。来世は木か石になりたいです</p>
    <div class="skills">
      <h2>Skills</h2>
      <h3>👍ﾜﾀｼﾁｮｯﾄﾃﾞｷﾙ</h3>
      <div class="good">
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
      <h3>👀興味がある</h3>
      <div class="curios">
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
  flex-wrap: wrap;
}
.skills {

}

.skills .good{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-flow: row;
  flex-wrap: wrap;
  margin-bottom: 1.5em;
}

.skills .curios{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-flow: row;
  flex-wrap: wrap;
  margin-bottom: 1.5em;
}

.skills h2 {
}

.tag {
  background-color: #52B3D9;
  border-radius: 5px;
  margin-right: 0.4em;
  margin-bottom: 0.4em;
  padding: 0.25em;
  color: #2C3E50;
  justify-content: flex-start;
}
</style>
