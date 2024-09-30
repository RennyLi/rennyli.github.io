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

Hello! I am Jingquan Li, but you can call me Renny if that's easier. I'm a fourth-year Computer Science undergraduate student at [The Chinese University of Hong Kong, Shenzhen](https://www.cuhk.edu.cn/en), supervised by [Prof. Haizhou Li](https://sds.cuhk.edu.cn/en/teacher/498) in the [Human Language Technology Lab](https://sds.cuhk.edu.cn/en/article/588), focusing on EEG Signal Processing and Deep Learning for Auditory Neuroscience. 

Additionally, I am working with [Prof. Pengcheng An](https://scholar.google.com/citations?user=8NN-2uYAAAAJ&hl=en) at the [AI-Deal Studio Lab](https://anpengcheng.cn/) of [SUSTech](https://www.sustech.edu.cn/en/), where I led a project on AIGC-Driven Approaches for Memory Assistance and Human-AI Interaction.

At [Shenzhen Research Institute of Big Data (SRIBD)](https://www.sribd.cn/en) under the supervision of [Prof. Xiang Wan](https://www.sribd.cn/en/teacher/28), I am involved in Multimodal Fusion and Data Augmentation for Neonatal Asphyxia Prediction.

I also collaborated with [Prof. Gang Cao](https://www.suat-sz.edu.cn/info/1166/1788.htm) at the [Shenzhen University of Advanced Technology](https://suat-sz.edu.cn/en/), working on Protein Interaction Prediction: Deep Learning Benchmarking and Visualization.

Advancements in AI and neuroscience are unlocking new possibilities in how we understand human behavior and improve societal well-being. From enhancing everyday interactions through human-computer collaboration to addressing critical healthcare challenges with biomedical AI, these innovations are shaping the future of education, health, and communication. By leveraging these technologies thoughtfully, we can create more effective, accessible solutions for complex human-centered problems.

My research focuses on integrating Human-AI Interaction and Auditory Neuroscience to improve well-being, education, and healthcare. To be specific, I am motivated by the following topics:
- Human-AI Collaboration: Exploring Human-Computer Interaction (HCI) and Human-Centered Computing (HCC) to enhance collaboration in education and public health through AI-driven tools.
- -Emotion and Auditory Processing: Using EEG and deep learning to decode emotions and auditory attention, with applications in Brain-Computer Interfaces (BCI) and communication aids.
- Biomedical AI: Applying machine learning and bioinformatics for biomedical signal processing and medical imaging to advance diagnostics and healthcare.

I am actively seeking Ph.D. positions starting in Fall 2025. If you are looking for a dedicated and self-motivated candidate, please feel free to contact me at jingquanli@link.cuhk.edu.cn.

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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">May 2024</div><img src='images/project3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Protein-protein interaction prediction using deep learning models**

[Shenzhen University of Advanced Technology](https://suat-sz.edu.cn/en/), Supervised by [Prof. Gang Cao](https://www.suat-sz.edu.cn/info/1166/1788.htm)

- Construct Non-redundant Sequences: Use CD-HIT to select the longest sequence from each group with a 0.7 similarity threshold, reducing positive samples from 8602 to 3880 and negative samples from 8490 to 3844. This decreases data volume and saves computational resources.
- Literature Review: Review studies using protein sequences or structures for predicting protein interactions. Summarize models, methods, datasets, and results, and explore protein feature embedding techniques for developing a PPI prediction model.
- Model Testing and Analysis: Evaluate open-source PPI prediction models on public datasets (yeast, E. coli, human). Analyze, compare, and summarize the model predictions and results.
</div>
</div>

# 📝 Academic projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Jan 2022</div><img src='images/project4.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Enhancing Recruitment Operations through Database Management**

[The Chinese University of Hong Kong, Shenzhen](https://www.cuhk.edu.cn/en), Supervised by [Prof. Clement Leung](https://sse.cuhk.edu.cn/en/faculty/clementleung)  [**GitHub**](https://github.com/RennyLi/Job-application-and-recruitment-platform-website-frontend)  [**PDF**](https://cuhko365-my.sharepoint.com/:b:/g/personal/119010148_link_cuhk_edu_cn/EUSEOy8I2QdMkH_7Qg8tmnwBqDchzg3aitFZB0saYX4IGw?e=zDRUet)

- Database Design and Creation: Created E-R diagrams to manage relationships between applicants, jobs, companies, and applications. Defined SQL schema and created tables to ensure data integrity and performance.
- Front-end Development and Back-end Integration: Designed a user-friendly interface using HTML and CSS. Enabled website-database interaction via PHP for user registration, information retrieval, and updates.
- Utilization of Large Language Models (LLMs): Used ChatGPT-4 to optimize database design and generate efficient SQL queries. Enhanced overall database structure with LLMs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Feb 2024</div><img src='images/project5.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Bremen Big Data Challenge 2024**

[Cognitive Systems Lab of Bremen University](https://www.uni-bremen.de/en/csl), Supervised by [Prof. Haizhou Li](https://www.uni-bremen.de/en/u-bremen-excellence-chairs/overview/prof-haizhou-li) 

- Data preprocessing and visualization: Conducted thorough data preprocessing and visualization to clean and prepare the dataset for analysis, which involved handling missing values, normalizing data, and creating visual representations to understand data distributions and trends.
- Convolutional Neural Network for context and affect prediction: Utilized Convolutional Neural Networks (CNNs) to capture complex patterns and relationships in the data.
- Performance evaluation and accuracy: Evaluated the performance of the predictive models, achieving an accuracy of 49.74% (highest accuracy: 58.54%).
</div>
</div>

# 💻 Internships
**2022.07 - 2022.12, [Search Technology Center Asia (STCA), Microsoft]((https://www.microsoft.com/en-us/ard/aboutus/team-stca)), Beijing, China**

User Growth Product Manager, Leader: Xinwei Nie(聂鑫伟)

- Contribute to Bing plug-in development in CJK areas: Researched on search engine and browser homepage plug-ins that perform well in CN market. Collected and organized user operation processes. Collaborated with the extension team in crafting Bing extensions for the Chrome browser.
- Research on input methods: Investigated in how mobile input methods like Baidu, Sogou, and Naver guide users to search engines and information flow pages. Evaluated Microsoft Swiftkey and propose improvement ideas. Generated a competitive product report.
- Research on Bing translation plug-in: Investigated in four popular Chrome translation plug-ins (Google Translate, Saladict, LingoCloud, DeepL). Summarized their functions, and survey users to rank the frequency of using these functions. Drafted a PRD for the Bing plug-in.

**2022.12 - 2023.6, [Feishu/Lark People, ByteDance](https://www.larksuite.com/en_us?from_site=feishu), Guangzhou, China**

People Customer Operation, Leader: Yuxuan Guo(郭玉瑄)

- Analyze high-frequency work order issues: Analyzed root causes of issues related to business operations and platform administration through collaboration across departments. Provided optimization ideas to enhance system stability and user satisfaction.
- Initiate demand review discussions: Gathered 300+ customer feetback on Feishu Recruitment , and independently initiated discussions to clearly communicate with the R&D team. Assessed the necessity and feasibility of requirements and followed up on the implementation of 100+ features.
- Develop usage documentation and training materials: Created comprehensive guides for payroll and HR back-end systems. Detailed functionalities and common troubleshooting strategies, in order to enhance users’ understanding and optimize their experience.

**2022.03 - 2022.07, [Weixin Group, Tencent](https://www.tencent.com/en-us/), Guangzhou, China**

Product Operation, Leader: Lin Lin(林琳)

- Write requirements and communicate: Drafted design requirement documents for ”20:15” and ”Cloud Stage” activities. Communicated with marketing and PR departments as well as conducting user dissemination via the WeChat official account.
- Analyze competitive products: Classified anchors from external sites based on rating standards and summarize popular topics. Conducted live broadcast competitive product analysis and summarized high-quality anchors. Developed content planning and operation ideas for internal activities.
- Write activity documents: Analyzed anchor supply sources, live broadcast traffic distribution, and rebroadcast rate. Wrote a project document for “Everything has a lesson” in collaboration with the marketing department to assist in the recruitment of event anchors.

# 🎖 Honors and Awards
- *2024.03* 2024 Bremen Big Data Challenge Global Top 10 Ranking
- *2022.12* 2022 Tencent Lighthouse Project Product Competition
- *2021.10* 2021 Honorable Award of National Undergraduate Mathematical Modeling Competition
- *2020.08* 2020 Chinese University of Hong Kong, Shenzhen Diligentia College Shanqun Scholarship

# 📖 Educations
- *2019.09 - 2025.05 (Expected)*, B.Eng. Candidate, School of Data Science, The Chinese Uiversity of Hong Kong, Shenzhen
- *Related Courses*, Machine Learning, Software Engineering, Database Systems, General Biology, General Chemistry, Mechanics, Probability and Statistics, Linear Algebra, Digital Logic and Systems

# 💬 Additionals
- *Languages*: TOEFL: 94 (Speaking: 23, Writing: 25)
- *Programming Languages*: Python, Matlab, Latex, Markdown
- *Libraries and Tools*: PyTorch, Sklearn, Pandas, Numpy, Git, TensorFlow
- *Other skills*: Web Dev, quantitative and qualitative data analysis, interfae design (Figma), fine-tuning

