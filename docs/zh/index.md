<style>
/* 通用样式 */
.section {
  padding: 40px 20px;
}
.section h2 {
  font-weight: bold;
  text-align: center;
  margin-bottom: 20px;
}
.section a {
  text-decoration: none;
  color: inherit;
  transition: all 0.3s ease;
}
.section a:hover {
  filter: brightness(1.1);
}

/* 第一栏：个人简况 */
.personal-info {
  display: flex;
  background-color: #f0f0f0;
  padding: 10px;
  align-items: center;
  border-radius: 2%;
}
.personal-photo {
  flex: 0.8;
  text-align: left;
}
.personal-photo img {
  width: 120px;
  height: 175px;
  object-fit: cover;
  border-radius: 8px;
}
.personal-details {
  flex: 1.2;
  padding: 0 20px;
  text-align: left;
}
.personal-details p {
  margin: 12px 0;
}
.education {
  flex: 2;
  background-color: #f0f0f0;
  padding: 3px;
  border-radius: 2%;
}

/* 第二栏：科研成果简述 */
.research {
  background-color: seashell;
  text-align: center;
  border-radius: 2%;
}
.research .paper-link img {
  width: 40px;
  transition: all 0.3s ease;
}
.research .paper-link img:hover {
  box-shadow: 0 0 10px #333;
  transform: scale(1.1);
  border-radius: 8px;
}

/* 第三栏：项目概览 */
.projects {
  background-color: seashell;
  text-align: center;
  position: relative;
  border-radius: 2%;
}
.project-carousel {
  position: relative;
  max-width: 600px;
  margin: auto;
}
.project-slide {
  display: none;
}
.project-slide img {
  width: 100%;
  border-radius: 8px;
  transition: all 0.3s ease;
}
.project-slide img:hover {
  transform: scale(1.05);
  box-shadow: 0 0 15px #333;
}
.project-title {
  font-weight: bold;
  font-size: 30px;
  margin-top: 10px;
}
.project-title:hover {
  text-shadow: 0 0 5px #555;
}
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  padding: 10px;
  margin-top: -20px;
  color: white;
  font-size: 70px;
  background-color: rgba(0,0,0,0.4);
  border-radius: 10%;
  transition: all 0.3s;
}
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.7);
  transform: scale(1.5);
}
.prev { left: -80px; }
.next { right: -80px; }
.dots {
  text-align: center;
  margin-top: 10px;
}
.dot {
  height: 12px;
  width: 12px;
  margin: 0 5px;
  display: inline-block;
  border-radius: 50%;
  background-color: transparent;
  border: 2px solid white;
  cursor: pointer;
}
.active {
  background-color: white;
}

/* 第四栏：获奖经历 & 第五栏：专利 */
.awards, .patents, .intern {
  text-align: center;
}
.awards { background-color: seashell; border-radius: 2%;}
.patents { background-color: seashell; border-radius: 2%;}
.intern { background-color: seashell; border-radius: 2%;}
.card {
  background-color: white;
  margin: 15px auto;
  padding: 20px;
  max-width: 600px;
  border-radius: 8px;
  transition: all 0.3s ease;
}
.card:hover {
  box-shadow: 0 0 12px #333;
  transform: scale(1.02);
}
</style>

---

## **个人简况**

<!-- 第一栏：个人简况 -->
<div class="section personal-info">
  <div class="personal-photo" flex="0.8">
    <img src="assets/my_photo.jpg" alt="个人照片">
  </div>
  <div class="personal-details" flex="1.5">
    <p><b>姓名：</b> 杨再正</p>
    <p><b>出生年月：</b> 1999-04</p>
    <p><img src="assets/address_icon.png" alt="地址图标" width="15" vertical-align="middle"> 南京市鼓楼区</p>
    <p><img src="assets/email_icon.png" alt="邮箱图标" width="15" vertical-align="middle"> zhisan.yang@qq.com</p>
    <p><img src="assets/phone_icon.png" alt="电话图标" style="width:15px; vertical-align:middle;"> 13951723161</p>
  </div>
  <div class="education" flex="1">
    <p><b>教育背景</b></p>
    <ul>
      <li>2015 - 2019 南京大学物理学院 学士</li>
      <li>2019 - 2025 南京大学物理学院 博士</li>
    </ul>
      <p><strong>博士研究方向</strong></p>
      <p>基于模拟存内计算硬件的深度学习推理系统</p>
  </div>
</div>

---

## **科研成果简述**

<!-- 第二栏：科研成果简述 -->
<div class="section research">
  <p>我博士期间的研究方向是基于模拟存内计算硬件（ReRAM, SRAM）的深度学习推理系统。已在<strong>Nature Electronics</strong>、<strong>Nature Nanotechnology</strong>、<strong>Science Advances</strong>等国际知名期刊发表论文7篇，
  另有两篇<strong>Nature Electronics</strong>、<strong>Science Robotics</strong>第一作者论文正在接受同行评审。</p>
  <h2><strong>论文列表</strong> <img src="assets/arrow_icon.png" alt="箭头图标" style="width:25px; vertical-align:middle;"></h2>
  <a href="https://scramblingsnail.github.io/CurriculumVitae/papers" class="paper-link">
    <img src="assets/paper_icon.png" alt="论文图标" style="width:80px; vertical-align:middle;">
  </a>
</div>

---

## **项目概览**

<!-- 第三栏：项目概览 -->
<div class="section projects">
  <div class="project-carousel">

    <div class="project-slide">
      <a href="https://scramblingsnail.github.io/CurriculumVitae/programs/rl_reram">
        <img src="assets/rl_reram.png" alt="项目1">
        <div class="project-title">ReRAM阵列测试系统 & 基于强化学习的ReRAM阻态编程方案</div>
      </a>
    </div>

    <div class="project-slide">
      <a href="https://scramblingsnail.github.io/CurriculumVitae/communication_aware_nn">
        <img src="assets/communication-aware.png" alt="项目2">
        <div class="project-title">基于SRAM模拟存内计算硬件的边云无线协同推理系统</div>
      </a>
    </div>

    <div class="project-slide">
      <a href="https://scramblingsnail.github.io/CurriculumVitae/programs/fully_analog_nn">
        <img src="assets/analog_nn.png" alt="项目3">
        <div class="project-title">基于模拟存内计算硬件的全模拟域人工神经网络（FNN,RNN,CNN）</div>
      </a>
    </div>

    <div class="project-slide">
      <a href="https://scramblingsnail.github.io/CurriculumVitae/programs/labridge">
        <img src="assets/labridge.png" alt="项目4">
        <div class="project-title">Labridge--搭建实验室沟通的桥梁</div>
      </a>
    </div>

    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
    <a class="next" onclick="plusSlides(1)">&#10095;</a>
  </div>

  <div class="dots">
    <span class="dot" onclick="currentSlide(1)"></span>
    <span class="dot" onclick="currentSlide(2)"></span>
    <span class="dot" onclick="currentSlide(3)"></span>
    <span class="dot" onclick="currentSlide(4)"></span>
  </div>
</div>

---

## **获奖经历**

<!-- 第四栏：获奖经历 -->
<div class="section awards">
  <a href="https://scramblingsnail.github.io/CurriculumVitae/awards/best_poster_award"><div class="card">3rd IEEE International Workshop on Future Computing 2019, <strong>Best Poster Award</strong></div></a>
  <a href="https://scramblingsnail.github.io/CurriculumVitae/awards/ascend2023"><div class="card">华为昇腾AI创新大赛2023全国总决赛 算法创新赛道 <strong>金奖×2</strong></div></a>
  <a href="https://scramblingsnail.github.io/CurriculumVitae/awards/ascend2024"><div class="card">华为昇腾AI创新大赛2024主赛道 江苏赛区 <b>银奖第一名(3/54)</b></div></a>
</div>

---

## **已授权专利**

<!-- 第五栏：已授权专利 -->
<div class="section patents">
  <a href="https://scramblingsnail.github.io/CurriculumVitae/patents/ca_patent"><div class="card">一种基于忆阻交叉阵列的机器人控制系统及方法 (专利号：CN110842915A)</div></a>
  <a href="https://scramblingsnail.github.io/CurriculumVitae/patents/us_patent"><div class="card">System and method for robot control based on memristive crossbar array (U.S. Patent 12,011,833 B2)</div></a>
</div>

---

## **实习经历**
<div class="section intern">
  <a href="https://scramblingsnail.github.io/CurriculumVitae/intern"><div class="card">华为昇腾Mindspore实习（2024.5-2024.11）</div></a>
</div>

---

<script>
let slideIndex = 1;
showSlides(slideIndex);
function plusSlides(n) { showSlides(slideIndex += n); }
function currentSlide(n) { showSlides(slideIndex = n); }
function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("project-slide");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " active";
}
</script>