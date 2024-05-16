---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.comment{
    background: white;
    color: #BD2A2E;
    font-size: 12px;
    padding: 1px 5px 1px 5px;
    border-radius: 0px;
    float: left;
    font-weight: bold;
}
</style>

<span class='anchor' id='about-me'></span>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}


I am currently a postdoctoral associate at Duke University, working with Prof. Yiran Chen and Prof. Hai (Helen) Li. I obtained my Ph.D. degree from the Computer Science and Engineering (CSE) at Shanghai Jiao Tong University in Sep. 2023, under the supervision of Prof. Jingwen Leng. My research interests include computer architecture and high-performance computing. I have published more than 10 papers at international conferences with a total of <a href='https://scholar.google.com/citations?user=sp5VwJoAAAAJ'>the Google Scholar citations <strong><span id='total_cit'>200</span></strong></a> (You can also use Google Scholar badge <a href='https://scholar.google.com/citations?user=sp5VwJoAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). 


# 🔥 News
- *2024.03*: &nbsp;🎉🎉🎉  I have been selected to be the recipient of the 2023 Shanghai Jiao Tong University Outstanding Doctoral Dissertation Award, [15 winners in 2023 at SJTU](https://www.gs.sjtu.edu.cn/yxbslw).
# 📝 Publications 
- ``ASPLOS 2024`` [GMLake: Efficient and Transparent GPU Memory Defragmentation for Large-scale DNN Training with Virtual Memory Stitching](https://arxiv.org/abs/2401.08156), **Cong Guo**, Rui Zhang, Jiale Xu, Jingwen Leng, Zihan Liu, Ziyu Huang, Minyi Guo, Hao Wu, Shouren Zhao, Junping Zhao, Ke Zhang;
- ``ASPLOS 2024`` [JUNO: Optimizing High-Dimensional Approximate Nearest Neighbour Search with Sparsity-Aware Algorithm and Ray-Tracing Core Mapping](https://arxiv.org/abs/2312.01712), Zihan Liu, Wentao Ni, Jingwen Leng, Yu Feng, **Cong Guo**, Quan Chen, Chao Li, Minyi Guo, Yuhao Zhu;
- ``TC 2024`` [Accelerating Sparse DNNs Based on Tiled GEMM](https://arxiv.org/abs/2402.10876), **Cong Guo**, Fengchen Xue, Jingwen Leng, Yuxian Qiu, Yue Guan, Weihao Cui, Quan Chen, Minyi Guo;
- ``ISCA 2023`` [OliVe: Accelerating Large Language Models via Hardware-friendly Outlier-Victim Pair Quantization](https://arxiv.org/abs/2304.07493), **Cong Guo**, Jiaming Tang, Weiming Hu, Jingwen Leng, Chen Zhang, Fan Yang, Yunxin Liu, Minyi Guo, Yuhao Zhu;[![](https://img.shields.io/github/stars/clevercool/ANT-Quantization?style=social&label=Code+Stars)](https://github.com/clevercool/ANT-Quantization)
- ``Micro 2022`` <span style="color:red">(2023 IEEE Micro Top Picks Honorable Mention)</span> [ANT: Exploiting Adaptive Numerical Data Type for Low-bit Deep Neural Network Quantization](https://arxiv.org/abs/2208.14286), **Cong Guo**, Chen Zhang, Jingwen Leng, Zihan Liu, Fan Yang, Yunxin Liu, Minyi Guo, Yuhao Zhu;[![](https://img.shields.io/github/stars/clevercool/ANT-Quantization?style=social&label=Code+Stars)](https://github.com/clevercool/ANT-Quantization) 

- ``ICLR 2022`` [SQuant: On-the-Fly Data-Free Quantization via Diagonal Hessian Approximation](https://arxiv.org/abs/2202.07471), **Cong Guo**, Yuxian Qiu, Jingwen Leng, Xiaotian Gao, Chen Zhang, Yunxin Liu, Fan Yang, Yuhao Zhu, Minyi Guo;[![](https://img.shields.io/github/stars/clevercool/SQuant?style=social&label=Code+Stars)](https://github.com/clevercool/SQuant)
- ``ICCD 2022`` [Nesting Forward Automatic Differentiation for Memory-Efficient Deep Neural Network Training](https://arxiv.org/abs/2209.10778), **Cong Guo**, Yuxian Qiu, Jingwen Leng, Chen Zhang, Ying Cao, Quanlu Zhang, Yunxin Liu, Fan Yang, Minyi Guo;
- ``MSN 2022`` <span style="color:red">(Best Paper Award)</span> [Towards Reliable AI Applications via Algorithm-Based Fault Tolerance on NVDLA](https://www.computer.org/csdl/proceedings-article/msn/2022/645700a736/1LUtObKmgko), Mustafa Tarik Sanic, **Cong Guo**, Jingwen Leng, Minyi Guo, Weiyin Ma; 
  
- ``IISWC 2021`` [Characterizing and Demystifying the Implicit Convolution Algorithm on Commercial Matrix-Multiplication Accelerators](https://arxiv.org/abs/2110.03901), Yangjie Zhou, Mengtian Yang, **Cong Guo**, Jingwen Leng, Yun Liang, Quan Chen, Minyi Guo, Yuhao Zhu;
- ``ISCA 2021`` [Dual-side Sparse Tensor Core](https://arxiv.org/abs/2105.09564), Yang Wang, Chen Zhang, Zhiqiang Xie, **Cong Guo**, Yunxin Liu, Jingwen Leng;
- ``SC 2022`` [Accelerating Sparse DNN Models without Hardware-Support via Tile-Wise Sparsity](https://arxiv.org/abs/2008.13006), **Cong Guo**, Bo Yang Hsueh, Jingwen Leng, Yuxian Qiu, Yue Guan, Zehuan Wang, Xiaoying Jia, Xipeng Li, Minyi Guo, Yuhao Zhu; [![](https://img.shields.io/github/stars/clevercool/TileSparsity?style=social&label=Code+Stars)](https://github.com/clevercool/TileSparsity)
- ``DAC 2020`` [Balancing Efficiency and Flexibility for DNN Acceleration via Temporal GPU-Systolic Array Integration](https://arxiv.org/abs/2002.08326), **Cong Guo**, Yangjie Zhou, Jingwen Leng, Yuhao Zhu, Zidong Du, Quan Chen, Chao Li, Bin Yao, Minyi Guo; 
- `CVPR 2019` [Adversarial Defense Through Network Profiling Based Path Extraction](https://openaccess.thecvf.com/content_CVPR_2019/html/Qiu_Adversarial_Defense_Through_Network_Profiling_Based_Path_Extraction_CVPR_2019_paper.html), Yuxian Qiu, Jingwen Leng, **Cong Guo**, Quan Chen, Chao Li, Minyi Guo, Yuhao Zhu;
  

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards

- *2024.03* Outstanding Doctoral Dissertation Award, Shanghai Jiao Tong University
- *2023.07* IEEE Micro Top Picks from Computer Architecture Conferences Honorable Mention
- *2023.06* Outstanding Doctoral Student Award, Shanghai Jiao Tong University
- *2022.08* Excellent Ph.D. Scholarship of Yang Yuanqing Education Fund (Top-3/500+), Shanghai Jiao Tong University
- *2020.11* Ph.D. National Scholarship (Top-8/500+), Ministry of Education, PRC
- *2020.07* DAC2020 Richard Newton Young Student Fellow, Design Automation Conference    
- *2018.11* VMware Scholarship, Shanghai Jiao Tong University
- *2017.11* National Second Prize, The 14th China Post-Graduate Mathematical Contest in Modeling
  
# 📖 Educations
- *2020.09 - 2023.09*, Ph.D in Computer Science and Technology, Department of Computer Science and Engineering, Shanghai Jiao Tong University.
- *2017.09 - 2020.03*, M.E. in Computer Technology, Department of Computer Science and Engineering, Shanghai Jiao Tong University.
- *2012.09 - 2016.06*, B.S. in Computer Science and Technology, College of Computer Science and Software Engineering, Shenzhen University.


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Work Experience

- *2023.12 - Now*, Postdoctoral associate, Department of ECE, Duke University.
  
- *2020.06 - 2021.05*, Research intern, Microsoft Research Asia (Beijing).
  
<!-- - Project 1: Design a Dual-side Sparse Tensor Core to support dual-side sparse matrix multiplication. Published in ISCA 2021.
- Project 2: Design a low-precision cache compression approach for accelerating DNN training and inference. Published in
ICCD 2022.
- Project 3: Design a new adaptive numerical data type for low-bit DNN quantization. Published in Micro 2022.
- Project 4: Design an on-the-fly data-free quantization method to significantly improve the model accuracy and accelerate the quantization processing. Published in ICLR 2022. -->
  
- *2019.05 - 2019.12*, Intern, NVIDIA (Shanghai).
  
<!-- - Intern: NVIDIA (Shanghai) May 2019 - Dec. 2019
  - Design a structured sparse pruning method according to the characteristics of the neural network;
  - Efficiently implements the structured pruning method on the GPU Tensor Core to accelerate the inference stage of the neural network. Published in SC 2020. -->