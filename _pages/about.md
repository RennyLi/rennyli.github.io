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

Hello! I am Jingquan Li, but you can call me Renny if that's easier. I'm a fourth-year Computer Science undergraduate student at [The Chinese University of Hong Kong, Shenzhen](https://www.cuhk.edu.cn/en), supervised by [Prof. Haizhou Li](https://sds.cuhk.edu.cn/en/teacher/498) in the [Human Language Technology Lab](https://sds.cuhk.edu.cn/en/article/588), focusing on auditory attention detection from EEG signals. Additionally, I am honored to be a member of the Medical Big Data Lab at [Shenzhen Research Institute of Big Data (SRIBD)](https://www.sribd.cn/en), where I work with [Prof. Xiang Wan](https://www.sribd.cn/en/teacher/28), exploring medical imaging with machine learning methods. Besides, I am also grateful to [Prof. Pengcheng An](https://scholar.google.com/citations?user=8NN-2uYAAAAJ&hl=en) and [Prof. Gang Cao](https://www.suat-sz.edu.cn/info/1166/1788.htm) for providing me with research opportunities in human-computer interaction and biomedical engineering using AI.

My research interests are primarily in human-computer interaction and machine learning. To be specific, I am motivated by the following topics:
- Natural language processing: Selective auditory attention detection based on EEG signals.
- Human-Computer interaction：Focusing on human-AI interaction, generative AI, education, and therapeutic AI.
- Machine learning in biomedical engineering: Integrating electronic medical records, medical imaging, health check reports and multi-omics data to aid pre-diagnosis and personalized treatment using machine learning technologies.

I am actively seeking Ph.D. positions starting in Fall 2025. If you are looking for a dedicated and motivated candidate, please feel free to contact me at jingquanli@link.cuhk.edu.cn.

Beyond my academic persuits, I am a passionate music enthusiast and a band drummer. I enjoy metalcore and fusion music, with Bring Me The Horizon and ONE OK ROCK being my favorite bands.

Thank you for taking the time to learn about me. I look forward to connecting and exploring how we can collaborate to make a positive impact through technology and our shared passions!

<!--
# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
-->

# 📝 Research Experience

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Mar 2024</div><img src='images/project1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Auditory attention detection based on EEG signals**

[Human Language Technology Lab](https://sds.cuhk.edu.cn/en/article/588), Supervised by [Prof. Haizhou Li](https://sds.cuhk.edu.cn/en/teacher/498)

- Literature Review and Data Foundation: Integrate and compare EEG decoding studies from the past decade, focusing on spatial localization, to establish a solid, data-driven foundation for future research.
- Data Collection and Preprocessing: Use cEEGrid devices for high-quality ear-EEG signal collection and preprocess public EEG datasets by removing artifacts and downsampling to enhance data quality for model training.
- Model Training and Visualization: Apply various deep learning models (attention-based, CNN-based, RNN-based, ML-based) on public datasets to predict attention direction and trajectory, and use visual tools to present experimental processes and findings clearly.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">July 2024</div><img src='images/project2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**AI-Assisted Fetal Heart Monitoring**

[Medical Big Data Lab](https://www.sribd.cn/en/znyy/medical), Supervised by [Prof. Xiang Wan](https://www.sribd.cn/en/teacher/28)

- Data Cleaning and Preprocessing: Handle missing values and anomalies in fetal heart rate (FHR) signals using interpolation, and clean private medical data with median filtering to create smooth and comprehensive datasets.
- Model Prediction and Evaluation: Predict fetal pH values using various models (KNN, SVM, Random Forest, XGBoost), noting that the Transformer model underperformed due to insufficient data.
- Wavelet Transform and Image Classification: Apply Continuous Wavelet Transform (CWT) on FHR signals, convert them into images, and train a ResNet50 model for classification, achieving an AUC improvement from 0.48 to 0.77.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">July 2024</div><img src='images/project2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Protein-protein interaction prediction using deep learning models**

[Shenzhen University of Advanced Technology](https://suat-sz.edu.cn/en/), Supervised by [Prof. Gang Cao](https://www.suat-sz.edu.cn/info/1166/1788.htm)

- Construct Non-redundant Sequences: Use CD-HIT to select the longest sequence from each group with a 0.7 similarity threshold, reducing positive samples from 8602 to 3880 and negative samples from 8490 to 3844. This decreases data volume and saves computational resources.
- Literature Review: Review studies using protein sequences or structures for predicting protein interactions. Summarize models, methods, datasets, and results, and explore protein feature embedding techniques for developing a PPI prediction model.
- Model Testing and Analysis: Evaluate open-source PPI prediction models on public datasets (yeast, E. coli, human). Analyze, compare, and summarize the model predictions and results.
</div>
</div>

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
