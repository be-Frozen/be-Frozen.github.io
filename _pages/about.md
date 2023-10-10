---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
I am a junior student in the [School of Computer and Electronic Information/School of Artificial Intelligence](http://schools.njnu.edu.cn/computer/) at Nanjing Normal University. My primary research interests are AI, data science, visualization,  and Human Computer Interaction. If you are seeking any form of **academic cooperation**, please feel free to email me at [isguodong.chen@outlook.com](mailto:isguodong.chen@outlook.com).

At Nanjing Normal University, I'm fortunate to work as a research assistant in Data-Driven XR Visualization Group led by Professor [Richen Liu (刘日晨)](https://dabigtou.github.io/richenliu/) and Computer Vision and Pattern Recognition Lab led by Professor [Fengyi Song (宋凤义)](http://schools.njnu.edu.cn/computer/person/fengyi-song). Click here to view my [CV](https://be-Frozen.github.io/files/Guodong_Chen_CV_Final 10_9.pdf).

# 🔥 News

<font color='red'>I will apply for PhD programs this Fall. If you have openings in your group, please feel free to reach out to me! </font>

- *2023.06*: &nbsp;🎉 One patent application has been accepted by the authorities.

# 📖 Educations

- *2020.09 - Now*, Undergraduate, Nanjing Normal University, China
- *2017.09 - 2020.06*, High-School Student, Wenzhou High School, China

# 📝 Patent 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">VIS 2023</div><img src='images/patent.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Medical data visualization method based on histogram and nonlinear embedded transfer function](https://patents.google.com/patent/CN116206735A/en?)

Yu Zhu, Richen Liu, Xinru Li, Shuyu Bao, Xiaojian Chen, **Guodong Chen**, Rongxin Cang, Xiaohan Wang, Siyu Yan, Xiaojun Qian. *CN116206735A, 2023*.


</div>
</div>

# 💡 Research Background

**Mini-Cloud Resource Managing System Development**, *Jul. 2023 - Aug. 2023*

*Online Project-based Learning (PBL), Interdisciplinary Research*

*Participant, Co-supervised by Prof. Maheswaran (McGill University) and Prof. Franchitti (New York University)*

- Reviewed extensive journal publications concerning Docker container concepts and familiarized myself with the fundamental concepts such as instantiation and management;

- Created and managed a mini-cloud resource manager containing 8 containers to process extensive datasets exceeding 1,000,000 records in cloud computing environments;

- Incorporated TensorFlow machine learning libraries into the derived system noted above to enable linear regressionmodeling on sample datasets.

**Automated Hierarchical Object Detection Method for Fine Annotation of Subcomponents**, *Sept. 2022 - Mar. 2023* 

*Nanjing Normal University*

*Research Assistant, Supervised by Prof. Fengyi Song*

- Reviewed extensive hierarchical object detection papers;

- Built a deep-learning model (based on Faster RCNN) that analyzes hierarchical relationships between data of objects for object detection and evaluated the model’s performance using our physics experiment dataset;

- Optimized the model and reduced missed detections and false alarms for small objects by 7% percent;

- Assessed the model’s performance (including latency, mAP, Quality of Experience, etc.) for small object detection.

**Interactive Visualization of Biomedical Data in both Immersive Environment & Extended Reality (XR)**, *Oct. 2021 - Sept. 2022*

*Data-Driven XR Visualization Group, Nanjing Normal University* 

*Research Assistant, Supervised by Prof. Richen Liu*

- Developed an immersive platform (in virtual reality) for medical diagnostics and transformed computerized topography inspection reports into 3D medical volume data. 

- Implemented advanced gesture-recognition technology to the project and realized touchless control of both angles and locations of volumetric medical data for viewing.

- Developed a system to support MR (Mixed Reality) medical diagnosis.

**Interactive Multi-user Medical Visualization and Immersive Volume Rendering**, May. *2021 - Dec. 2021*

*Data-Driven XR Visualization Group, Nanjing Normal University* 

*Research Assistant, Supervised by Prof. Richen Liu*

- Optimized a ray-casting algorithm and then deployed the derived algorithm to immersive environments for 3d medical volumetric data interpretation;

- Implemented a track seeding algorithm (based on the continuous scale space theory) to facilitate 2D to 3d imaging migration;

- Generated 3D textures from the seeding algorithm subsequent to multi-user interactions and then tested multi-user rendering of 3D volumetric data in an immersive environment.

# 👨‍🎓 Teaching Experience

- *Fall, 2023*, Teaching Assistant, [Machine Learning Course](https://aistudio.baidu.com/education/group/info/29088), Nanjing Normal University
- *2021.09 - 2023.06*, Assistant Mentor, School of Computer and Electronic Information, Nanjing Normal University

# 📚 Selected Projects

**[Cracking Wordle: Predicting Wordle Results](https://github.com/be-Frozen/Cracking-Wordle)** 

*A Solution to the Problem C of 2023 MCM/ICM*

- Developed Prophet, Multilayer Perceptron, and K-Means Clustering models to forecast future Wordle results and associated percentage scores, as well as to categorize word difficulty; achieved high accuracy, especially for predicting word difficulty, reaching close to 90% precision.

- Designed an innovative Normal Distribution Principle Components Analysis algorithm to ensure the accuracy of the models noted above.

- Awarded Meritorious Winner award in 2023 MCM/ICM.

**[Agridentify: Agricultural Object Detection Model Based on PP-YOLOE+ and Copy-Paste](https://aistudio.baidu.com/projectdetail/5726879)** 

*18th National University Student Intelligent Vehicle Competition*

- Developed an agricultural object detection model (using PaddlePaddle-YOLOE+) and trained the model on a dataset of 8 types of agricultural objects with 4770 samples.

- Utilized Copy-Paste data augmentation to improve detection accuracy from 85% to around 95%.

- Achieved a top-10% finish during the competition with a best F1-score of 0.98913, with an F1-score within 0.005 of the winning team.

**[VueForum: a BBS forum with PHP front-end and Vue framework back-end](https://github.com/be-Frozen/XDBBS)** 

*Team Leader, Software Engineering Course project*

- Developed a functional forum website with user interaction capabilities and implemented the back-end functions using Vue framework and integrated MySQL database access.

- Earned an A+ grade for the course.

# 🎖 Honors and Awards

- *2023.05* Meritorious Winner, 2023 Mathematical Contest in Modeling
- *2023.04* First Prize, Feng Ruer Scholarship, Nanjing Normal University
- *2023.03* Technology Star, Nanjing Normal University
- *2022.11* First Prize, Excellent Student Scholarship, Nanjing Normal University
- *2022.11*Third Prize, China Collegiate Mathematics Competition, Jiangsu Division
- *2022.08* Third Prize, China Collegiate Computer Design Contest
- *2022* Merit Student, Nanjing Normal University

# 🎮 Hobbies

Football, Game Design, Video Editing

# 🗺 Map of Visitors

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=500&t=n&d=5mBmdKPFJ0xWDDQbhq0UR0fCSOwFOOVqpCB-cCobtfU'></script>

<p style="text-align:right;font-size:small;" >Last updated: Oct. 10, 2023</p>

<!-- <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
  <tr>
    <td style="padding:0px">
      <br>

      <p style="text-align:right;font-size:small;">
      Template stolen from <a href="https://github.com/RayeRen/acad-homepage.github.io" style="social">AcadHomepage</a> 
      <br> Last updated: Jul 6, 2023 
      </p>
​    </td>
  </tr>
</tbody></table> -->