---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- {% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %} -->
<span class='anchor' id='about-me'></span>
Nice to meet you here! Hope to be friends with you.

My name is Shuai MAO. I'm currently a third-year graduate student at [Xi’an Jiaotong University](http://eie.xjtu.edu.cn/en/index.htm), on track to graduate in the summer of 2024. I previously obtained my bachelor's degree in Information Engineering from Xi'an Jiaotong University in 2021. During my sophomore year, I decided to broaden my cultural horizons and expand my social network. Consequently, I enrolled in a double degree program, which took me to [CentraleSupélec](https://www.centralesupelec.fr/en) from 2019 to 2021. Curriculum at CentraleSupélec emphasized the fusion of theory and practice. While studying the course, I developed an intense passion for mathematics. This newfound interest served as the catalyst for me to seize the opportunity to advance my studies in mathematics at University of Paris XI. To accommodate this additional academic pursuit, I carefully managed my time, attending regular classes during the day and dedicating my evenings to mastering mathematics. My persistence and hard work ultimately paid off when I achieved high scores in my CentraleSupélec courses and successfully passed the challenging mathematics examinations. Although this period was undeniably demanding, it brought me immense satisfaction and joy in the pursuit of my academic goals.

My current research centers around ghost imaging, which is also referred to as quantum imaging or correlated imaging. Unlike traditional first-order-based imaging algorithms, this innovative imaging technique relies on second-order correlations within the light field, specifically the fluctuations in intensity. While it offers advantages such as being lensless, robust against disturbances, and non-localized in nature, the current approach demands a substantial number of measurements, thus restricting its practical utility. My research efforts are primarily directed toward optimizing ghost imaging algorithms. Throughout this research journey, I have not only developed a profound understanding of ghost imaging but have also acquired knowledge in areas such as image processing, compressed sensing, optimization techniques, inverse problems, and deep learning. Among these, deep learning has emerged as my most powerful tool in advancing the field. On one hand, I am astounded by its remarkable effectiveness. On the other hand, I also recognize the importance of enhancing our comprehension of the fundamental nature of deep learning to ensure that its power does not inadvertently harm people.

I am currently eagerly anticipating opportunities for PhD positions in 2024, particularly in the fields of image processing, computer vision, Explainable AI (XAI), and responsible AI. If you want to find more information about me, you can find my [CV](../files/MAO_SHUAI.pdf) here.

# 📖 Educations
- *2021.09 - 2024.06 (now)*, MEng Communication and Information System at [Xi’an Jiaotong University](http://eie.xjtu.edu.cn/en/index.htm), [transcript](../files/transcript_of_postgraduate_student.pdf). 
- *2019.09 - 2024.06*, French engineer at [CentraleSupélec](https://www.centralesupelec.fr/en) ([Paris Saclay University](https://www.universite-paris-saclay.fr/en) now), [transcript](../files/transcript_of_centralesupelec.pdf). 
- *2019.10 - 2020.06*, BSc Mathematics at University of Paris XI ([Paris Saclay University](https://www.universite-paris-saclay.fr/en) now), [transcript](../files/transcript_of_math.pdf)
- *2017.09 - 2021.06*, BEng Information Engineering at [Xi’an Jiaotong University](http://eie.xjtu.edu.cn/en/index.htm). [transcript](../files/transcript_of_graduate.pdf)

# 📝 Publications 
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
[High-quality and high-diversity conditionally generative ghost imaging based on denoising diffusion probabilistic model](../files/High-quality_and_high-diversity_conditionally_generative_ghost_imaging_based_on_denoising_diffusion_probabilistic_model.pdf)

**Shuai Mao**, Yuchen He, Hui Chen, et al.  **Optics Express**

In this paper, I pioneered the use of diffusion models in ghost imaging, particularly focusing on the undersampled scenario where a set of bucket signals can correspond to multiple potentially correct images. Traditional deterministic deep learning models are limited to one-to-one mapping in such cases. To address this challenge, I skillfully incorporated bucket signals as prior information for the image distribution. This approach led to the creation of an innovative ghost imaging reconstruction algorithm capable of learning the conditional probability distribution of the image, taking into account the known bucket signals.

[Translation-Equivalence-Based Unsupervised Ghost Imaging](../files/Translation-Equivalence-Based_Unsupervised_Ghost_Imaging.pdf)

**Shuai Mao**, Yuchen He, Jianming Yu, et al.  **IEEE International Conference of Information and Communication Technology**

In this paper, I investigated the translation equivalence property and devised an unsupervised ghost imaging algorithm. This innovation allows for efficient image reconstruction without requiring labels.

[Fully-Connected-Based Adaptive Speckles Optimization Method for Ghost Imaging](../files/Fully-Connected-Based_Adaptive_Speckles_Optimization_Method_for_Ghost_Imaging.pdf)

Zhou Yu, **Shuai Mao**, Yuchen He, et al.  **IEEE Photonics Technology Letters**

In this paper, I introduced an innovative approach where measurement speckles are treated as fully connected layer parameters without bias. Utilizing end-to-end network learning, the measurement speckles gain prior information about the targets. Extracting parameters from the fully connected layer as the measurement speckles enables high-quality image reconstruction even at lower sampling rates.

[Optimizing speckles for dynamic objects using genetic algorithm in ghost imaging](../files/Optimizing_speckles_for_dynamic_objects_using_genetic_algorithm_in_ghost_imaging.pdf)

Yuchen He, **Shuai Mao**, Juan Chen, et al.  **AIP Advances**

In this paper, I conducted an in-depth exploration of the intricate relationship between speckles and measurement, employing genetic algorithms to select adaptive speckles for dynamic targets.
 
# 💻 Internships
## *2023.06 - 2023.09*, Backend Developper Summer Intern, [Mei Tuan](https://www.meituan.com/en-US/about-us), China.

During my internship as a Java Developer at Meituan, I played a pivotal role in driving the growth and innovation of the back-end business while concurrently contributing to network security enhancement. Here's an overview of my key responsibilities and accomplishments:

1. Interface Risk Assessment: I spearheaded the development of an interface risk assessment system aimed at evaluating network interface vulnerability to crawler attacks. This initiative involved several key achievements: conducting comprehensive curve similarity analysis to identify recurring traffic patterns, adopting the Pearson correlation as the core of our security assessment model, establishing a seamless online-to-offline data integration process for daily risk calculations, and scaling the system to assess the security of over 2,000 interfaces, effectively reducing the risk of malicious web crawler attacks.

2. JSON Parsing and Performance Analysis: I delved deeply into the realm of JSON parsing techniques and harnessed the potent capabilities of Java Microbenchmarking Harness (JMH) for conducting comprehensive performance analyses. Through testing, we meticulously evaluated the parsing speed across various methods for JSON strings of differing sizes and nesting levels. This exploration not only broadened our comprehension of efficient data processing but also yielded invaluable insights crucial for optimizing our systems to attain peak performance.

3. Store hot list evaluation：To bolster our system's promotion capabilities, I crafted RPC and HTTP interfaces for hot list evaluation. I leveraged CompletableFuture for asynchronous processing of Excel data streams, facilitating the evaluation of nearly 20,000 stores efficiently. Concurrently, I introduced a secondary category field, completed the transformation of response interfaces and databases, and enabled precise store classification.

## *2022.07 - 2023.08*, Hardware Reliability Intern, [Amazon China](https://www.aboutamazon.com/what-we-do/devices-services), China.

During my internship at Amazon, I had the chance to dive into the important world of hardware reliability. This field is all about making sure products are not only well-designed but also safe and long-lasting for users.

My internship started with research on common low-power chargers available in the market. To get a better grasp of what's out there, I analyzed twelve chargers from four well-known brands. My main aim was to carefully assess how reliable these chargers were. This included investigating their ultrasonic welding methods, their thickness, efforts to make them more compact, their handling of electrical aspects like capacitance, and their safety features such as fuses.

In my role, I actively promoted teamwork within the group. I shared my research findings with my colleagues, and together, we collaborated on various projects to make improvements. Armed with the knowledge I gained, we enhanced our products to ensure they not only perform well but are also safe for users. This played a pivotal role in helping Amazon maintain its competitive edge in the market, all while putting user satisfaction and safety first.

When I look back on my time at Amazon, I take immense pride in being part of a company that places such a strong emphasis on creating reliable and safe products. This experience reinforced my belief in the importance of designing products that are user-friendly and safe for everyone. It continues to motivate me to use my skills to be accountable to users and ensure their safety.

# 🎖 Honors and Awards
- *2022 and 2023* [Chiang Chen Scholarship](http://www.ccicf.org.hk/en/scholarships/fellowship_b_06/) (15 students in total). 
- *2021.06* Excellent Graduate, Excellent Student of Xi’an Jiaotong University. 
- *2018 and 2019* [Cyrus Tang Scholarship](https://tangfoundation.org/cyrus-tang-foundation/ct-scholarship/introduction/) (40 students in total). 
- *2018.01* Excellent Volunteer of Blood Donation Service in Xi'an Central Blood Station.

# 🔧 Skills
- *Languages*    English (Bilingual, IELTS 7.5), French (Fluent, DELF B2)
- *Programming Languages*    Java, Python, Golang, MATLAB, SQL 
- *Software/Tools*    LaTeX, Excel, Word, Powerpoint, Git, Spring, Pytorch

# 💭 More About Me
Before entering college, I lived in a small town and devoted the majority of my time to preparing for the highly competitive college entrance examination, which attracted nearly one million candidates from my province each year. Fortunately, I achieved outstanding scores and secured admission to a prestigious university in China, marking my initial step into a broader world.

Over the past six years, serendipity has guided me through diverse fields, including communications, mathematics, electromagnetic fields, ghost imaging, and computers. I've been fortunate to partake in both hardware and software internships. While specialized knowledge may fade with time, my unwavering commitment to excellence remains a constant in my current endeavors.

Please don't perceive my diverse interests as a lack of direction; rather, they reflect my fervent desire to explore and acquire knowledge. Each path I traverse presents a new adventure, and genuine experiences are essential for genuine understanding. As such, I wholeheartedly embrace opportunities to broaden my horizons and deepen my knowledge, one step at a time.

I readily embrace starting from scratch and possess the ability to learn quickly. Each new experience molds me into an improved version of myself.

In addition to the experiences mentioned above, I served as a teaching assistant for digital logic circuits from January to June 2022. In this role, I graded coursework, provided constructive feedback to students, and conducted exercise classes to address their questions and offer detailed explanations for homework. I also supervised course attendance, fostering a positive learning environment and offering support. Additionally, I worked as a student assistant in the school's Employment and Entrepreneurship Center, where I welcomed students seeking consultation, assisted teachers with daily tasks, and aided in organizing company presentations.

In my leisure time, I take pleasure in immersing myself in books authored by various writers. Their stories possess the remarkable ability to transport me to different worlds. Some of my favorite authors include Juan Li from China, Fredrik Backman from Sweden, Marc Levy from France, Hiroshi Yuuki from Japan, and Ito Ogawa, also from Japan. If you're interested, I'd be delighted to recommend some of their books to you as well.