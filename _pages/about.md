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

我博士毕业于北京 中国农业大学 信息与电气工程学院。包括合著，我已经发表 12+ 篇学术论文
 <a href='https://scholar.google.com.hk/citations?user=2--440wAAAAJ&hl=zh-CN'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>。

我的研究领域包括：
- 计算机视觉
- 深度学习
- 三维重建
- 农业机器人
- 植物表型
  


<span class='anchor' id='-xl'></span>

# 🎓 学历
- *2021.12 - 2022.12*, <a href="https://www.uni-bonn.de/en/"><img class="svg" src="images/1200px-Universität_Bonn.svg.png" width="23pt"></a>  波恩大学 大地测量与地理信息系, 德国, CSC博士联合培养
- *2018.09 - 2023.07*, <a href="https://www.cau.edu.cn/"><img class="svg" src="images/1200px-CAU_Logo.svg.png" width="23pt"></a> 中国农业大学 信息与电气工程学院, 北京, 博士
- *2016.09 - 2018.06*, <a href="https://www.nwafu.edu.cn/"><img class="svg" src="images/Northwest_A&F_University.svg.png" width="20pt"></a> 西北农林科技大学 信息工程学院, 陕西杨凌, 硕士
- *2012.09 - 2016.06*, <a href="https://www.nwafu.edu.cn/"><img class="svg" src="images/hbnu.svg.png" width="20pt"></a> 湖北师范大学 计算机与信息工程学院, 湖北黄石, 学士 
<span class='anchor' id='-lwzl'></span>

# 📝 论文专利

### 期刊论文
---

- Si Yang, Lihua Zheng, Huijun Yang, Man Zhang, Tingting Wu, Shi Sun, Federico Tomasetto, Minjuan Wang*. A synthetic datasets based instance segmentation network for High-throughput soybean pods phenotype investigation[J]. Expert Systems with Applications, 2022, 192: 116403. (JCR 1 区，中科院 1 区 Top，影响因子 8.6644)
- Si Yang, Lihua Zheng, Peng He, Tingting Wu, Shi Sun, Minjuan Wang. High-throughput soybean seeds phenotyping with convolutional neural networks and transfer learning[J]. Plant Methods, 2021, 17(1): 1-17. (JCR 1 区，中科院 2 区，影响因子 5.8271)
- Si Yang, Lihua Zheng, Wanlin Gao, et al. An Efficient Processing Approach for Colored Point Cloud-Based High-Throughput Seedling Phenotyping[J]. Remote Sensing, 2020, 12(10): 1540. (JCR 1 区，中科院 2 区 Top，影响因子 5.3493)
- Yu Zhang, Mengliu Wu, Jinsong Li, Si Yang, et al., Automatic non-destructive multiple lettuce traits prediction based on DeepLabV3+[J]. Journal of Food Measurement and Characterization (2022): 1-17. (JCR 3 区，中科院 3 区，影响因子 3.0059)
- Xia Hao, Jingdun Jia, Jiaqi Mi, Si Yang, Abdul Mateen Khattak, Lihua Zheng, Wanlin Gao, Minjuan Wang*. An optimization model of light intensity and nitrogen concentration coupled with yield and
quality[J]. Plant Growth Regulation, 2020, 92(2): 319-331. (JCR 2 区，中科院 3 区，影响因子: 3.2418)
- 王跃亭,王敏娟,孙石,杨斯,郑立华.基于图像处理和聚类算法的待考种大豆主茎节数统计[J].农业机械学报,2020,51(12):229-237. (EI)
- 杨斯,高万林,米家奇,吴梦柳,王敏娟,郑立华.基于RGB-D相机的蔬菜苗群体株高测量方法[J].农业机械学报,2019,50(S1):128-135. (EI)
- 杨斯,黄铝文*,张馨*.机器视觉在设施育苗作物生长监测中的研究与应用[J].江苏农业科 学,2019,47(06):179-187.
- Si Yang, Lihua Zheng, Tingting Wu, Shi Sun, Man Zhang, Minzan Li, Minjuan Wang. RefinePod: towards high throughput soybean pods high-quality segmentation and seed-per-pod estimation for plant breeding[J]. Engineering Applications of Artificial Intelligence, (major revise, JCR 1 区，中科院 2 区 Top，
影响因子 7.8024)
- Si Yang, Peng He, Laura Zabawa, Xieyuanli Chen, Lihua Zheng, Minjuan Wang, Lasse Klingbeil, Heiner Kuhlmann. Multi-view depth image based high quality 3D plant organ instance segmentation[J].
(under review)

### 会议论文
---

- Si Yang, Lihua Zheng, Xieyuanli Chen, Laura Zabawa, Man Zhang, Minjuan Wang*. Transfer Learning from Synthetic In-vitro Soybean Pods Dataset for In-situ Segmentation of On-branch Soybean Pod[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2022. (CCF A workshop)
- Si Yang, Lihua Zheng, Minjuan Wang*, Frédéric Boudon, Tingting Wu, Shi Sun, Peng He. Segmentation and recognition of high throughput soybean pods with a supervised edge attention network and synthetic datasets to extract pod harvestability traits [C]//CVPPA-ICCV. 2021. (CCF A workshop)
- Mengliu Wu, Lihua Zheng, Yongjie Chen, Si Yang, Jiaqi Mi, Minjuan Wang*. Time-series change detection model of lettuce canopy area in a controlled environment[C]//2020 ASABE Annual International Virtual Meeting. American Society of Agricultural and Biological Engineers, 2020: 1. (EI)
- Jiaqi Mi, Wanlin Gao, Si Yang, Xia Hao, Minzan Li, MInjuan Wang, Lihua Zheng* (2019). A Method of
Plant Root Image Restoration Based on GAN. IFAC-PapersOnLine, 52(30), 219-224. (EI)

### 专利
---
- 郑立华, 米家奇, 王敏娟, 吴梦柳, 杨斯等. 基于生成对抗网络的根系图像修复方法[P]. 北京： ZL201910642641.X, 2021-9-21.（发明专利授权）
- 王敏娟, 师圣铎, 杨斯等. 一种适用于科研学习的通用外壳装置[P]. 北京：ZL202022220682.0, 2021-6-1.（实用新型专利授权）
- 高万林, 王兵兵, 杨斯等. 基于无线传感器节点的分簇方法、系统、设备及存储介质[P]. 北京： ZL202010136527.2, 2021-11-30.（发明专利授权）






<span class='anchor' id='-ryjx'></span>

# 🏅 荣誉奖项
- *2021* 获得 中国博士研究生国家奖学金 
- *2021* 获得 中国留学基金委（CSC）博士生奖学金 
- *2020-2022* 连续三年获得中国农业大学一等学业奖学金
- *2019* 获得 中国农业大学二等学业奖学金
- *2019* 获得 智慧农业创新发展国际研讨会-学术会议Excellent Presentation
- *2017* 获得 西北农林科技大学“优秀研究生”
- *2016-2017* 连续两年获得西北农林科技大学二等学业奖学金

<span class='anchor' id='-xshy'></span>

# 🏛️ 学术会议
- *2022*, 第七届国际植物表型大会 (IPPS 2022), 荷兰瓦赫宁根, 海报+全英文口头汇报
- *2022*, DGK PhD Seminar Engineering Geodesy Division, 德国克劳斯塔尔
- *2022*, 第三届国际研讨会和挑战-农业视觉：计算机视觉在农业中的挑战与机遇 (CVPR2022), 线上, 论文
- *2022*, 可持续作物生产数字技术国际会议 (DIGICROP 2022), 德国波恩
- *2021*, 第七届植物表型和农业计算机视觉研讨会 (CVPPA@ICCV 2021), 线上, 论文
- *2021*, 第六届寿光国际设施园艺会, 山东寿光, 海报
- *2020*, 第一届北美植物表型学会年会 (NAPPN2020 2019), 线上, 长摘要
- *2019*, 第六届国际植物表型大会 (IPPS 2019), 江苏南京, 海报
- *2019*, 智慧农业创新发展国际研讨会 (ICSaid 2019), 北京, 全英文口头汇报

<span class='anchor' id='-gzsx'></span>

# 💻 工作实习
<!-- - *2018.05 - 2020.02*, 重庆长江轴承股份有限公司, 重庆
- *2020.11.25 - 2020.12.02*, 湖北新冶钢有限公司, 湖北黄石
- *2017.6 - 2021.1*, 制造装备数字化国家工程研究中心, 湖北武汉 -->
