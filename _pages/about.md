---
permalink: /
title: "关于 | About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
layout: single
---

<div class="lang-zh">
<p><strong>张宇飞 (Yufei Zhang)</strong> — Columbia University 机械工程硕士，研究方向包括机器人学、强化学习、康复机器人与多模态人机交互。</p>
<p><strong>联系方式</strong><br>电话：(+1) 646-713-5164<br>邮箱：<a href="mailto:yz4917@columbia.edu">yz4917@columbia.edu</a><br>LinkedIn：<a href="https://www.linkedin.com/in/zyffbk">linkedin.com/in/zyffbk</a><br>地址：425 Summit Ave, Jersey City, NJ 07306, USA</p>
<p><strong>文档</strong> — <a href="/files/Yufei%20Zhang_CV.pdf">简历</a> · <a href="/files/transcript/transcript.pdf">成绩单</a> · <a href="/files/publication/">论文 PDF</a></p>

<h3>教育背景</h3>
<p><strong>Columbia University</strong> — 08/2024–至今，硕士 (GPA 3.75/4.00)<br><strong>UC San Diego</strong> — 09/2023–01/2024，交换<br><strong>北京工业大学</strong> — 08/2020–07/2024，机器人工程学士 (专业 GPA 3.85/4.00)</p>

<h3>工作经历</h3>
<p><strong>中科院自动化所</strong> — 06/2022–09/2023，嵌入式工程师实习生。参与基于强化学习的灵巧手操作项目；将控制框架移植到 FreeRTOS，实现 RL 部署所需的低延迟控制；集成 PPO/SAC 策略与硬件控制器。</p>
<p><strong>微软亚洲研究院</strong> — 01/2022–02/2022，MSRA 研究员。参与多语言对话生成项目；使用 mBART、mT5 等模型；集成 Azure Neural TTS 与数字人管线。</p>

<h3>学术项目与经历</h3>
<ul>
<li><strong>Columbia: 5-DOF 马术康复系统</strong> (09/2025–至今) — RA，Prof. Sunil K. Agrawal。5 自由度康复平台动力学建模与仿真。</li>
<li><strong>Columbia: LipSyncBot 多伺服视位控制</strong> (02/2025–至今) — RA，Prof. Hod Lipson。多自由度唇部机构与 TTS 口型同步管线。</li>
<li><strong>Columbia: 3-RRR 踝关节康复机器人</strong> (02/2025–至今) — 研究生，Prof. Sunil K. Agrawal。球面并联机构设计、动力学与柔顺控制。</li>
<li><strong>Columbia: Robotics Studio</strong> (02/2025–06/2025) — TA，Prof. Hod Lipson。指导 80+ 学生四足/仿生机器人设计，PyBullet、PPO、sim-to-real。</li>
<li><strong>人形机器人实时盲运动去模糊</strong> (09/2023–06/2024) — 本科毕设，北工大，Prof. Naigong Yu。MoUGAN，36.36 dB PSNR，0.9211 SSIM。</li>
<li><strong>基于改进 A* 的寻球车</strong> (03/2023–06/2023) — 编程与嵌入式。改进 A*、SLAM、视觉检球、ROS 与 PID。</li>
<li><strong>迁移强化学习用于燃气轮机转子故障诊断</strong> (12/2022–03/2023) — 独立作者，IEEE SMC 2023 (CCF-C)。Transfer-DQN，98.95% / 96.91% 准确率。</li>
<li><strong>RoboMaster 战队 (PIP)</strong> (08/2022–09/2023) — 电控负责人，北工大。Dart 系统、工程师机器人电气、步兵底盘与云台、Sentry SLAM、无人机；组织 50+ 新人培训。</li>
</ul>

<h3>项目链接 (Portfolio)</h3>
<ul>
{% for post in site.portfolio %}
<li><a href="{{ post.url }}">{{ post.title }}</a>{% if post.website %} — <a href="{{ post.website }}">网站</a>{% endif %}</li>
{% endfor %}
</ul>
<p>本站使用 <a href="https://jekyllrb.com/">Jekyll</a> 构建，托管于 <a href="https://pages.github.com/">GitHub Pages</a>。源码：<a href="https://github.com/YufeiZhang0601/YufeiZhang0601.github.io">GitHub</a>。</p>
</div>

<div class="lang-en">
<p><strong>Yufei Zhang</strong> — MS in Mechanical Engineering at Columbia University. Research interests: robotics, reinforcement learning, rehabilitation systems, and human-robot interaction.</p>
<p><strong>Contact</strong><br>Tel: (+1) 646-713-5164<br>E-mail: <a href="mailto:yz4917@columbia.edu">yz4917@columbia.edu</a><br>LinkedIn: <a href="https://www.linkedin.com/in/zyffbk">linkedin.com/in/zyffbk</a><br>Address: 425 Summit Ave, Jersey City, NJ 07306, USA</p>
<p><strong>Documents</strong> — <a href="/files/Yufei%20Zhang_CV.pdf">CV</a> · <a href="/files/transcript/transcript.pdf">Transcript</a> · <a href="/files/publication/">Publication PDFs</a></p>

<h3>Education</h3>
<p><strong>Columbia University</strong> — 08/2024–Present, MS (GPA 3.75/4.00)<br><strong>UC San Diego</strong> — 09/2023–01/2024, Exchange<br><strong>Beijing University of Technology</strong> — 08/2020–07/2024, BE in Robot Engineering (Major GPA 3.85/4.00)</p>

<h3>Professional Experience</h3>
<p><strong>Institute of Automation, Chinese Academy of Sciences</strong> — 06/2022–09/2023, Embedded Engineer Intern. RL-based dexterous manipulation; FreeRTOS real-time layer; PPO/SAC policy integration with hardware.</p>
<p><strong>Microsoft (China) MSRA</strong> — 01/2022–02/2022, MSRA Researcher. Multilingual dialogue generation; mBART, mT5; Azure Neural TTS and digital avatar pipeline.</p>

<h3>Academic Projects &amp; Research</h3>
<ul>
<li><strong>Columbia: 5-DOF Hippotherapy Rehabilitation System</strong> (09/2025–Present) — RA, Prof. Sunil K. Agrawal. Dynamic modeling and simulation of pelvic motion platform.</li>
<li><strong>Columbia: LipSyncBot, Multi-Servo Viseme Control</strong> (02/2025–Present) — RA, Prof. Hod Lipson. Multi-DOF lip mechanism and TTS-driven lip-sync pipeline.</li>
<li><strong>Columbia: 3-RRR Spherical Parallel Ankle Rehabilitation Robot</strong> (02/2025–Present) — Graduate Researcher, Prof. Sunil K. Agrawal. Mechanism design, dynamics, compliance.</li>
<li><strong>Columbia: Robotics Studio</strong> (02/2025–06/2025) — TA, Prof. Hod Lipson. Guided 80+ students in quadruped/bio-inspired robots; PyBullet, PPO, sim-to-real.</li>
<li><strong>Real-Time Blind Motion Deblurring for Humanoid Robot Vision</strong> (09/2023–06/2024) — Undergrad thesis, BJUT, Prof. Naigong Yu. MoUGAN, 36.36 dB PSNR, 0.9211 SSIM.</li>
<li><strong>Ball-Retrieval Car with Refined A* Algorithm</strong> (03/2023–06/2023) — Programming &amp; Embedded. A*, SLAM, vision-based ball detection, ROS, PID.</li>
<li><strong>Transfer Reinforcement Learning for Gas Turbine Rotor Fault Diagnosis</strong> (12/2022–03/2023) — Sole author, IEEE SMC 2023 (CCF-C). Transfer-DQN, 98.95% / 96.91% accuracy.</li>
<li><strong>RoboMaster Robotics Team (PIP), BJUT</strong> (08/2022–09/2023) — Electrical Control Lead. Dart system, Engineer Robot, Infantry chassis, Sentry SLAM, UAV; trained 50+ applicants.</li>
</ul>

<h3>Portfolio</h3>
<ul>
{% for post in site.portfolio %}
<li><a href="{{ post.url }}">{{ post.title }}</a>{% if post.website %} — <a href="{{ post.website }}">Website</a>{% endif %}</li>
{% endfor %}
</ul>
<p>This site is built with <a href="https://jekyllrb.com/">Jekyll</a> and hosted on <a href="https://pages.github.com/">GitHub Pages</a>. Source: <a href="https://github.com/YufeiZhang0601/YufeiZhang0601.github.io">GitHub</a>.</p>
</div>
