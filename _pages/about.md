---
permalink: /
title: "关于 | About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="lang-zh">

**张宇飞 (Yufei Zhang)** — Columbia University 机械工程硕士，研究方向包括机器人学、强化学习、康复机器人与多模态人机交互。

**联系方式**  
电话：(+1) 646-713-5164  
邮箱：[yz4917@columbia.edu](mailto:yz4917@columbia.edu)  
LinkedIn：[linkedin.com/in/zyffbk](https://www.linkedin.com/in/zyffbk)  
地址：425 Summit Ave, Jersey City, NJ 07306, USA

**文档** — [简历](/files/Yufei%20Zhang_CV.pdf) · [成绩单](/files/transcript/transcript.pdf) · [论文 PDF](/files/publication/)

### 项目与经历 (Portfolio)

{% for post in site.portfolio %}
* **[{{ post.title }}]({{ post.url }})** — {{ post.excerpt | strip_html | strip_newlines | truncate: 120 }} {% if post.website %}[网站]({{ post.website }}){% endif %}
{% endfor %}

本站使用 [Jekyll](https://jekyllrb.com/) 构建，托管于 [GitHub Pages](https://pages.github.com/)。源码见 [GitHub](https://github.com/YufeiZhang0601/YufeiZhang0601.github.io)。

</div>

<div class="lang-en">

**Yufei Zhang** — MS in Mechanical Engineering at Columbia University. Research interests: robotics, reinforcement learning, rehabilitation systems, and human-robot interaction.

**Contact**  
Tel: (+1) 646-713-5164  
E-mail: [yz4917@columbia.edu](mailto:yz4917@columbia.edu)  
LinkedIn: [linkedin.com/in/zyffbk](https://www.linkedin.com/in/zyffbk)  
Address: 425 Summit Ave, Jersey City, NJ 07306, USA

**Documents** — [CV](/files/Yufei%20Zhang_CV.pdf) · [Transcript](/files/transcript/transcript.pdf) · [Publication PDFs](/files/publication/)

### Portfolio

{% for post in site.portfolio %}
* **[{{ post.title }}]({{ post.url }})** — {{ post.excerpt | strip_html | strip_newlines | truncate: 120 }} {% if post.website %}[Website]({{ post.website }}){% endif %}
{% endfor %}

This site is built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/). Source: [GitHub](https://github.com/YufeiZhang0601/YufeiZhang0601.github.io).

</div>
