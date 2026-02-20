---
layout: archive
title: "简历 | CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

**下载 PDF：** 若您已将简历 PDF 放入 `files` 文件夹（如 `resume.pdf`），可在此提供下载链接：  
**[下载简历 PDF](/files/resume.pdf)**（请将您的 `resume.pdf` 放到项目根目录的 `files` 文件夹后即可使用）

---

教育背景 | Education
======
* （请在此填写：如 硕士/博士，学校，年份）
* （如：本科，学校，年份）

工作/实习经历 | Work Experience
======
* （请按时间倒序填写，例如：）
* 时间: 职位
  * 单位名称
  * 工作内容简述
  * 导师/主管（如有）

技能与兴趣 | Skills & Interests
======
* （技能或方向 1）
* （技能或方向 2）
* （技能或方向 3）

发表与项目 | Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

报告与演讲 | Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

教学 | Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

其他（服务、获奖等）| Service & More
======
* （可填写：学术服务、获奖、语言等）
