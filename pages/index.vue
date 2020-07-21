<template>
		<div class="styles">
  		<div class="sides">
				<a href="#profile" class="bar profile"><h4>PROFILE</h4></a>
				<a href="#skills" class="bar skills"><h4>SKILLS</h4></a>
				<a href="#fun" class="bar fun"><h4>FUN</h4></a>
				<a href="#active" class="bar active"><h4>ACTIVE</h4></a>
			</div>
      <div class="content">
        <a name="profile" />
        <div class="blank" />
        <div class="profiletxt">
          <h4>VANTAN TECHFORD ACADEMY 1</h4>
          <h1>murataak ポートフォリオ</h1>
          <h4>更新日 20/6/28</h4>
          <h2><br>このポートフォリオで使用している言語</h2>
          <h3>Vue.js + Nuxt.js + CSS</h3>
          <h2><br>拡張予定</h2>
          <h3><br>レスポンジブ対応</h3>
          <h3><br>Bootstrap-vue適応</h3>
          <h3><br>下記課題サイトの構築/SPA</h3>
          <h3>　twitterライクなサイト</h3>
          <h3>　youtubeライクなサイト</h3>
        </div>
        <a name="skills" />
        <div class="blank" />
        <div class="skillstxt">
          <h2>学習スキル</h2>
          <h3>HTML CSS</h3>
          <h3>python3</h3>
          <h3>Vue.js + Nuxt.js</h3>
          <h3>Elm</h3>
        </div>
        <a name="fun" />
        <div class="blank" />
        <div class="funtxt">
          <h2>趣味</h2>
          <h3><a href="https://worldoftanks.asia/ja/">World of Tanks</a></h3>
          <h3><a href="https://store.steampowered.com/app/236850/Europa_Universalis_IV/">Europa Universalis IV</a></h3>
          <h3><a href="https://store.steampowered.com/app/394360/Hearts_of_Iron_IV/">Hearts of Iron IV</a></h3>
        </div>
        <a name="active" />
        <div class="blank" />
        <div class="activetxt">
          <h2>SNS等外部ツール</h2>
          <h3><a href="https://twitter.com/ankoumurata">Twitter</a></h3>
        </div>
      </div>
  	</div>
</template>

<script>
export default {
	layout:'default'
}
</script>
<style>
.styles{
  position:relative;
  overflow:auto;
  display:flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: flex-start;
  align-content: flex-start;
  -ms-overflow: none;
  scrollbar-width: none;
  background: linear-gradient(to bottom, rgba(10, 1, 1, 0.12) 0%,rgba(27,32,48,1) 50%);
}
.styles::-webkit-scrollbar{
  display: none;
}
.sides{
  color:rgb(128, 118, 118);
}
.bar{
  left:2em;
  color:rgb(128, 118, 118);
  display:block;
  position:fixed;
  text-decoration:none
}
.bar.profile{
  top:5em;
}
.bar.skills{
  top:10em;
}
.bar.fun{
  top:15em;
}
.bar.active{
  top:20em;
}
.content{
  display: block;
  position: relative;
  justify-content: center;
  align-items: center;
  align-content: center;
}
.blank{
  margin-top: 10em;
}
.profiletxt{
  color:rgb(128, 118, 118);
}
.skillstxt{
  color:#696969;
}
.funtxt{
  color:#DCDCDC;
}
.activetxt{
color:azure;
}
h1{
  font-size:3em;
}
h2{
  font-size:2.5em;
}
h3{
  font-size:2em;
}
h4{
  font-size:1.5em;
}
</style>
