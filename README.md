<!-- Centered Introduction with Typing Effect and Animated Gradient Background -->
<h1 align="center">
  <span style="font-size: 3em; color: #ffffff;">
    <span id="typed-text"></span><span id="cursor">|</span>
  </span>
  <br>
  <span style="font-size: 1.5em; color: #ff8c00;">A Passionate Website Developer from Pakistan</span>
</h1>

<!-- Animated Tech Icons with a Wave Effect -->
<div align="center" style="margin: 30px 0;">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo" class="tech-icon" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript logo" class="tech-icon" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo" class="tech-icon" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo" class="tech-icon" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo" class="tech-icon" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/android/android-original.svg" height="40" alt="android logo" class="tech-icon" />
</div>

<!-- Social Media Links with a Pulsating Hover Effect -->
<div align="center" style="margin: 20px 0;">
  <a href="https://www.youtube.com/channel/UCOzD-c-Tbbo84lFpzLnSJrg" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="youtube logo" class="social-icon" />
  </a>
  <a href="https://www.instagram.com/reyanabid4/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="instagram logo" class="social-icon" />
  </a>
  <a href="mailto:reyanabid20@gmail.com" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo" class="social-icon" />
  </a>
  <a href="https://www.facebook.com/ReyanWebDevpore" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Facebook&logo=facebook&label=&color=1877F2&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="facebook logo" class="social-icon" />
  </a>
</div>

<!-- Floating Avatar with Glowing Gradient Border -->
<div align="right" style="margin: 20px 0;">
  <img src="https://camo.githubusercontent.com/7de37139d0b4c1ce40865e799b446c0e963a3dd8fb68d239707237c40604fa3d/68747470733a2f2f63646e2e6472696262626c652e636f6d2f75736572732f3733303730332f73637265656e73686f74732f363538313234332f6176656e746f2e676966" height="150" alt="floating avatar" style="border-radius: 50%; border: 5px solid; border-image: linear-gradient(to right, #ff8c00, #6a5acd) 1; box-shadow: 0px 0px 15px rgba(255, 140, 0, 0.8), 0px 0px 15px rgba(106, 90, 205, 0.8);" />
</div>

<!-- Snake Animation with Custom Design -->
<img src="https://raw.githubusercontent.com/reyanabid123/reyanabid123/output/snake.svg" alt="Snake animation" style="margin-top: 20px;" />

<!-- Profile Counter with 3D Shadow Effect -->
<div align="center" style="margin: 20px 0;">
  <img src="https://profile-counter.glitch.me/reyanabid123/count.svg?" alt="Profile counter" style="box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.3);" />
</div>

<!-- GitHub Stats with Smooth Appearance -->
<div align="center" style="margin: 20px 0;">
  <img src="https://github-readme-stats.vercel.app/api?username=reyanabid123&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=radical&locale=en&hide_border=false&order=1" height="150" alt="stats graph" class="stats-graph" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=reyanabid123&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=radical&hide_border=false&order=2" height="150" alt="languages graph" class="stats-graph" />
</div>

<!-- Latest Medium Posts with Hover Effect -->
<div align="center" style="margin: 20px 0;">
  <img src="https://github-read-medium-git-main.pahlevikun.vercel.app/latest?limit=4" alt="Layout with last medium posts" class="latest-posts" />
</div>

<!-- CSS for Animations and Effects -->
<style>
@keyframes typing { from { width: 0; } to { width: 100%; } }
@keyframes blink { 50% { border-color: transparent; } }
@keyframes wave { 0%, 100% { transform: translateY(0); } 50% { transform: translateY(-10px); } }
@keyframes pulse { 0% { transform: scale(1); } 50% { transform: scale(1.05); } 100% { transform: scale(1); } }
@keyframes statsAppear { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
#typed-text { display: inline-block; font-size: 3em; color: #ffffff; overflow: hidden; white-space: nowrap; border-right: 4px solid; width: 0; animation: typing 4s steps(40, end), blink 0.75s step-end infinite; }
.tech-icon { margin: 0 15px; animation: wave 3s infinite ease-in-out; }
.social-icon { margin: 0 10px; animation: pulse 2s infinite ease-in-out; }
.stats-graph { margin: 0 10px; animation: statsAppear 1.5s ease-out; }
.latest-posts { transition: transform 0.3s; }
.latest-posts:hover { transform: scale(1.05); }
</style>

<div id="typed-text"></div>

<script>
document.addEventListener('DOMContentLoaded', (event) => {
  const typedText = "Hi, I'm Reyan Abid";
  let index = 0;
  const typingSpeed = 100;
  function typeText() {
    if (index < typedText.length) {
      document.getElementById('typed-text').textContent += typedText.charAt(index);
      index++;
      setTimeout(typeText, typingSpeed);
    }
  }
  typeText();
});
</script>

