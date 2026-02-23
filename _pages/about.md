---
permalink: /
title: "🏠 Homepage – Yufei Zhang"
author_profile: true
redirect_from:
  - /about/
  - /about.html
layout: single
---

<div class="homepage-intro lang-en">
  <p class="homepage-name">Yufei Zhang (张宇飞)</p>
  <p class="homepage-affiliation">M.S. Student in Mechanical Engineering (Robotics Track)<br>Columbia University, New York</p>
  <p class="homepage-contact">
    Email: <a href="mailto:yz4917@columbia.edu">yz4917@columbia.edu</a><br>
    LinkedIn: <a href="https://www.linkedin.com/in/zyffbk" target="_blank" rel="noopener">linkedin.com/in/zyffbk</a><br>
    CV: <a href="/files/Yufei%20Zhang_CV.pdf">Download CV</a>
  </p>
  <hr class="homepage-sep" />
  <h2 class="homepage-h2">About Me</h2>
  <p>I am a Master's student in Mechanical Engineering at Columbia University, focusing on <strong>robotics</strong>, <strong>embodied intelligence</strong>, and <strong>reinforcement learning</strong>.</p>
  <p>My research interests lie at the intersection of:</p>
  <ul class="homepage-interests">
    <li>🤖 Intelligent robotic systems</li>
    <li>🧠 Learning-based control (RL / Transformer-based methods)</li>
    <li>🦾 Human–robot interaction</li>
    <li>🦿 Rehabilitation robotics</li>
    <li>👄 Expressive humanoid robotics</li>
  </ul>
  <p>I am particularly interested in building robots that can <strong>learn</strong>, <strong>adapt</strong>, and <strong>physically interact</strong> with humans in safe and expressive ways.</p>

  <h2 class="homepage-h2">📚 Educations</h2>
  <p class="homepage-edu-cat"><strong>Robotic Engineering</strong></p>
  <ul class="homepage-edu">
    <li><strong>Aug 2024 – Present.</strong> Columbia University, New York, NY, US
      <ul>
        <li>M.S. in Mechanical Engineering (Robotics Track), GPA: 3.8/4.00</li>
        <li>Courses: Advanced Spoken Language Processing, Robot Learning, Robotics Studio, Applied Robotics: Algorithms &amp; Software, Data Science for Mechanical Systems, Intro to Control Theory, Mechatronics &amp; Embedded Micro</li>
      </ul>
    </li>
    <li><strong>Sept 2023 – Jan 2024.</strong> University of California, San Diego (UCSD), San Diego, CA, US
      <ul>
        <li>Exchange Programme</li>
        <li>Courses: Natural Language Processing, Mathematics for Robotics, Engineering Hands-on Group Project</li>
      </ul>
    </li>
    <li><strong>Aug 2020 – Jul 2024.</strong> Beijing University of Technology (Project 211), Beijing, CN
      <ul>
        <li>B.E. in Robot Engineering, Overall Average Score: 89/100</li>
      </ul>
    </li>
  </ul>
</div>

<div class="homepage-intro lang-zh">
  <p class="homepage-name">张宇飞 (Yufei Zhang)</p>
  <p class="homepage-affiliation">机械工程硕士（机器人方向）<br>哥伦比亚大学，纽约</p>
  <p class="homepage-contact">
    邮箱：<a href="mailto:yz4917@columbia.edu">yz4917@columbia.edu</a><br>
    LinkedIn：<a href="https://www.linkedin.com/in/zyffbk" target="_blank" rel="noopener">linkedin.com/in/zyffbk</a><br>
    简历：<a href="/files/Yufei%20Zhang_CV.pdf">下载 CV</a>
  </p>
  <hr class="homepage-sep" />
  <h2 class="homepage-h2">关于我</h2>
  <p>我是哥伦比亚大学机械工程硕士生，研究方向为<strong>机器人</strong>、<strong>具身智能</strong>与<strong>强化学习</strong>。</p>
  <p>研究兴趣包括：</p>
  <ul class="homepage-interests">
    <li>🤖 智能机器人系统</li>
    <li>🧠 基于学习的控制（RL / Transformer 等方法）</li>
    <li>🦾 人机交互</li>
    <li>🦿 康复机器人</li>
    <li>👄 拟人化表情机器人</li>
  </ul>
  <p>尤其关注能够<strong>学习</strong>、<strong>适应</strong>并与人类<strong>安全、有表现力地交互</strong>的机器人系统。</p>

  <h2 class="homepage-h2">📚 教育背景</h2>
  <p class="homepage-edu-cat"><strong>机器人工程</strong></p>
  <ul class="homepage-edu">
    <li><strong>2024年8月 – 至今.</strong> 哥伦比亚大学，纽约，美国
      <ul>
        <li>机械工程硕士（机器人方向），GPA: 3.8/4.00</li>
        <li>课程：高级口语语言处理、机器人学习、机器人工作室、应用机器人算法与软件、机械系统数据科学、控制论导论、机电与嵌入式等</li>
      </ul>
    </li>
    <li><strong>2023年9月 – 2024年1月.</strong> 加州大学圣地亚哥分校 (UCSD)，美国
      <ul>
        <li>交换项目</li>
        <li>课程：自然语言处理、机器人数学、工程实践小组项目</li>
      </ul>
    </li>
    <li><strong>2020年8月 – 2024年7月.</strong> 北京工业大学（211），北京，中国
      <ul>
        <li>机器人工程学士，总平均分 89/100</li>
      </ul>
    </li>
  </ul>
</div>

<h3 class="lang-zh">项目详情 (点击进入)</h3>
<h3 class="lang-en">Portfolio (click to open)</h3>
<div class="grid__wrapper grid__wrapper--portfolio">
{% for post in site.portfolio %}
{% include archive-single-portfolio.html %}
{% endfor %}
</div>
