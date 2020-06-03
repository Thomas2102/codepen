<html>
<head>
<style>
body {
  background-color: red;
}
.navbar {
  overflow: hidden;
  background-color: black;
  position: fixed;
  top: 0;
  width: 100%;
}

.navbar a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.navbar a:hover {
  background: #ddd;
  color: black;
}

#welcome-section {
  background-color: blue;
  color: White;
  padding: 60px;
  text-align: center;
  height: 75vh;
}

#about-section {
  background-color: blue;
  color: White;
  padding: 15px;
  text-align: center;
  margin: 30px;
}

.project-tile {
  background-color: #8b0000;
  color: white;
  margin: 30px;
  padding: 20px;
}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.btn {
  display: inline-block;
  background: #f0f8ff;
  border: 0;
  line-height: 2.5em;
  padding: 0 0 0 1em;
  margin-bottom: 1em;
  outline: none;
  text-decoration: none;
  color: #dc143c;
}

  .arrow {
    display: inline-block;
    line-height: 2.5em;
    text-align: center;
    background: #696969;
    color: red;
    font-size: 1em;
    width: 2.5em;
    transition: margin 200ms;
    margin-left: .75em;
  }

body {
  background-color: red;
}

@media only screen and (max-width: 600px) {
  body {
    background-color: #000080;
  }
}
</style>
</head>
<body>

<section id="welcome-section"> <!-- Denne id'en representerer at dette er welcome-section på hjemme siden min-->
  <h1>Thomas's Website</h1>
</section>

<section id="about-section"> 
  <h1>My name is Thomas and i'm 18 years old, my interests are video games and enjoying being with friends. When i play, it's like i'm in another world, where everything is perfect</h1>
</section>

<section id="navbar">
  <div class="navbar">
    <a href="#welcome-section">Home</a>
    <a href="#projects">Projects</a>
    <a href="#about-section">About Me</a>
    <a class="active"  
     href="https://www.youtube.com/channel/UC3dvPcoUWcLijRz06yKxyJA?view_as=subscriber" target="_blank">Youtube</a>
  <a href="https://www.twitch.tv/crown_kryzo" target="_blank">Twitch</a>
  <a href=https://www.instagram.com/__kryzo/ target="_blank">Instagram</a>
</div>

<section id="projects">
  <div class="project-tile">
  <img src="http://icons.iconarchive.com/icons/uiconstock/socialmedia/72/YouTube-icon.png"
    <p>I make high level montages for games like Rocket League and Fortnite, Check out my <a href="https://www.youtube.com/channel/UC3dvPcoUWcLijRz06yKxyJA?view_as=subscriber" target="_blank">Youtube</a>
  </div>

<div class="project-tile">
  <img src="http://icons.iconarchive.com/icons/papirus-team/papirus-apps/72/gnome-twitch-icon.png"
    <p>I make high level montages for games like Rocket League and Fortnite, Check out my <a href="https://www.twitch.tv/crown_kryzo" target="_blank">Twitch</a>
  </div>
  
<div class="project-tile">
<img src="http://icons.iconarchive.com/icons/icons8/windows-8/64/Social-Networks-Instagram-icon.png"
    <p>I post highlighit clips on my Instagram, Check out my  <a href="https://www.instagram.com/__kryzo/" target="_blank">Instagram</a>
  </div>
  </section>
  
<section id="profile-link">
  <div class="right">
  <a href="https://github.com/Thomas2102" target="_blank" class="btn">GitHub profile <span class="arrow">❯</span></a>
  <br/>


<script>
document.getElementsByTagName("h1")[0].style.fontSize = "80px";
</script>
</body>
</html>
