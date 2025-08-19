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

Hi there! I am Hao Li (李昊 in Chinese), a fourth-year Ph.D. candidate in the School of Computer Science at Peking University, advised by [Prof. Li Yuan](https://scholar.google.com/citations?user=-5juAR0AAAAJ&hl=en). Before that, I got my Bachelor of Science degree in computer science at Peking University with a Summa Cum Laude.

My research interests include multimodal Learning, visual understanding, and AI for Chemical Science. I have published more than 20 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=y4va91AAAAAJ'> Google Scholar citations <strong><span id='total_cit'>1000+</span></strong></a>.


# 🔥 News
- *2025.06*: &nbsp;🎉🎉 We release **ChemCoTBench**, the first LLM-benchmark evaluating step-wise reasoning on complex chemical tasks.
- *2025.06*: &nbsp;🎉🎉 Our SUR-LID(https://github.com/beautyremain/SUR-LID) for Face Forgery Detection accepted by CVPR-2025.
- *2024.12*: &nbsp;🎉🎉 One papers accepted by **Nature Computational Science**.
- *2024.08*: &nbsp;🎉🎉 Two papers accepted by The 18th European Conference on Computer Vision(ECCV-2024).
- *2023.08*: &nbsp;🎉🎉 One paper accepted by The International Conference on Computer Vision(ICCV-2023).
- *2023.06*: &nbsp;🎉🎉 One paper accepted by Transactions on Image Processing(TIP).
- *2023.04*: &nbsp;🎉🎉 Three paper accepted by The International Joint Conference on Artifical Intelligence(IJCAI-2023).
- *2022.08*: &nbsp;🎉🎉 One oral paper accepted by The International Conference on Multimedia and Expo(ICME-2022-Oral).

# 📝 Selected Publications and Preprints
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/ChemCoTBench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Beyond Chemical QA: Evaluating LLM's Chemical Reasoning with Modular Chemical Operations](https://howardli1984.github.io/ChemCoTBench.github.io/)

**Hao Li**, He Cao, Bin Feng, Yanjun Shao, Xiangru Tang, Zhiyuan Yan, Li Yuan†, Yonghong Tian†, Yu Li†

[**Project**](https://github.com/HowardLi1984/ChemCoTBench) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Official Homepage for the ChemCoTBench, the first step-wise reasoning benchmark for LLMs in Chemical domain.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div><img src='images/HBI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hierarchical banzhaf interaction for general video-language representation learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10815073)

**Hao Li**, **Peng Jin**, Shuicheng Yan, Li Yuan†, Jie Chen†

[**Project**](https://github.com/jpthu17/HBI) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Official Homepage for the HBI, a new approach that models video-text as game players using multivariate cooperative game theory to handle uncertainty during fine-grained semantic interactions with diverse granularity, flexible combination, and vague intensity.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/FreestyleRet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FreestyleRet: Retrieving Images from Style-Diversified Queries](https://arxiv.org/abs/2312.02428)

**Hao Li**, Yanhao Jia, Peng Jin, Zesen Cheng, Kehan Li, Jialu Sui, Chang Liu, Li Yuan

[**Project**](https://github.com/CuriseJia/FreeStyleRet) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Official Code for the FreestyleRet framework. Official Released for the Diversified-Style Retrieval Dataset (DSR).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Nature Computational Science 2024</div><img src='images/ECDFormer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Decoupled peak property learning for efficient and interpretable ECD spectra prediction](https://www.nature.com/articles/s43588-024-00757-7)

**Hao Li**, Da Long, Li Yuan, Yu Wang, Yonghong Tian, Xinchang Wang, Fanyang Mo

[**Project**](https://github.com/HowardLi1984/ECDFormer) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Existing predictive approaches lack the consideration of ECD spectra due to the data scarcity, and the interpretability to achieve trust-worthy prediction. Here, we establish a large-scale dataset for Chiral Molecular ECD spectra (CMCDS) and propose ECDFormer for accurate and interpretable ECD spectra prediction. ECDFormer decomposes ECD spectra into peak entities, employs the QFormer architecture to learn peak properties, and renders peaks into spectra. Compared to spectra sequence prediction methods, our decoupled peak prediction approach substantially enhances both accuracy and efficiency, improving the peak symbol accuracy from 37.3% to 72.7% and decreasing the time cost from an average of 4.6 CPU hours to 1.5 seconds.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/DiffusionRet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Diffusionret: Generative text-video retrieval with diffusion model](https://openaccess.thecvf.com/content/ICCV2023/papers/Jin_DiffusionRet_Generative_Text-Video_Retrieval_with_Diffusion_Model_ICCV_2023_paper.pdf)

**Hao Li**, Peng Jin, Zesen Cheng, Kehan Li, Chang Liu, Li Yuan, Jie Chen

[**Project**](https://github.com/jpthu17/DiffusionRet) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Official Code for the DiffusionRet model.
</div>
</div>

# 🎖 Honors and Awards
- *2023.9* Hongqiao Scholarship in Peking University (Top 1%). 

# 📖 Educations
- *2017.09 - 2021.06*, Bachelor, in School of Electronics Engineering and Computer Science (EECS), Peking University.
- *2021.09 - 2023.09*, Master, School of Electronics and Computer Engineering (ECE), Peking University.
- *2023.09 - now*, PhD Candidate, School of Computer Science, Peking University.

# 💻 Internships
- *2020.07 - 2021.09*, Mentored by [Xu Li](https://scholar.google.com/citations?hl=en&user=qtSYO44AAAAJ&view_op=list_works&sortby=pubdate), Cognitive Computing Lab, Baidu Research, Beijing, China.
- *2022.07 - 2023.02*, Mentored by [Songyang Zhang](https://scholar.google.com/citations?user=8XQPi7YAAAAJ&hl=en&oi=ao), OpenMMLab, Shanghai AI Lab, Shanghai, China.
- *2024.12 - present*, Mentored by [Yu Li](https://scholar.google.com/citations?user=j9lwU7kAAAAJ&hl=en&oi=ao), International Digital Economy Academy, Shenzhen, China.
