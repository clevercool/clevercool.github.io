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


I am currently a postdoctoral associate at Duke University, working with Prof. Yiran Chen and Prof. Hai (Helen) Li. I obtained the Ph.D. degree from the Department of Computer Science and Engineering (CSE) at Shanghai Jiao Tong University in September 2023, under the supervision of Prof. Jingwen Leng. My research interests include computer architecture and high-performance computing. I have published more than 10 papers at international conferences with a total of  Google Scholar <a href='https://scholar.google.com/citations?user=sp5VwJoAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. 


# 🔥 News
- *2025.03*: &nbsp;🎉🎉🎉  Three papers are accepted by **ISCA 2025**.
- *2024.11*: &nbsp;🎉  Three papers are accepted by **HPCA 2025**.
- *2024.03*: &nbsp;🎉  I received the 2023 Shanghai Jiao Tong University **Outstanding Doctoral Dissertation Award**, [15 winners (<1%) per year.](https://www.gs.sjtu.edu.cn/yxbslw) ([2023年度上海交通大学优秀博士学位论文，全校共15人](https://www.gs.sjtu.edu.cn/yxbslw)).
- *2023.11*: &nbsp;🎉  Two papers are accepted by **ASPLOS 2024**.
  
# 📝 Publications 
### Conference:
- ``HPCA 2025`` Chiyue Wei, **Cong Guo**\*, Feng Cheng, Shiyu Li, Hao Yang, Hai Li, Yiran Chen; [Prosperity: Accelerating Spiking Neural Networks via Product Sparsity](https://arxiv.org/abs/2503.03379). (\*Corresponding Author)
[![](https://img.shields.io/github/stars/dubcyfor3/Prosperity?style=social&label=Code+Stars)](https://github.com/dubcyfor3/Prosperity)
- ``HPCA 2025`` Zihan Liu, Xinhao Luo, Junxian Guo, Wentao Ni, Yangjie Zhou, Yue Guan, **Cong Guo**, Weihao Cui, Yu Feng, Minyi Guo, Yuhao Zhu, Minjia Zhang, Jingwen Leng, Chen Jin; [VQ-LLM: High-performance Code Generation for Vector Quantization Augmented LLM Inference](https://arxiv.org/abs/2503.02236). 
- ``HPCA 2025`` Weiming Hu, Haoyan Zhang, **Cong Guo**, Yu Feng, Renyang Guan, Zhendong Hua, Zihan Liu, Yue Guan, Minyi Guo, Jingwen Leng; [MANT: Efficient Low-bit Group Quantization for LLMs via Mathematically Adaptive Numerical Type](https://arxiv.org/abs/2502.18755).
- ``ASPLOS 2024`` **Cong Guo**, Rui Zhang, Jiale Xu, Jingwen Leng, Zihan Liu, Ziyu Huang, Minyi Guo, Hao Wu, Shouren Zhao, Junping Zhao, Ke Zhang; [GMLake: Efficient and Transparent GPU Memory Defragmentation for Large-scale DNN Training with Virtual Memory Stitching](https://arxiv.org/abs/2401.08156). 
- ``ASPLOS 2024`` Zihan Liu, Wentao Ni, Jingwen Leng, Yu Feng, **Cong Guo**, Quan Chen, Chao Li, Minyi Guo, Yuhao Zhu; [JUNO: Optimizing High-Dimensional Approximate Nearest Neighbour Search with Sparsity-Aware Algorithm and Ray-Tracing Core Mapping](https://arxiv.org/abs/2312.01712). 
- ``ISCA 2023`` **Cong Guo**, Jiaming Tang, Weiming Hu, Jingwen Leng, Chen Zhang, Fan Yang, Yunxin Liu, Minyi Guo, Yuhao Zhu; [OliVe: Accelerating Large Language Models via Hardware-friendly Outlier-Victim Pair Quantization](https://arxiv.org/abs/2304.07493). 
[![](https://img.shields.io/github/stars/clevercool/ANT-Quantization?style=social&label=Code+Stars)](https://github.com/clevercool/ANT-Quantization)
- ``MICRO 2022`` **Cong Guo**, Chen Zhang, Jingwen Leng, Zihan Liu, Fan Yang, Yunxin Liu, Minyi Guo, Yuhao Zhu; [ANT: Exploiting Adaptive Numerical Data Type for Low-bit Deep Neural Network Quantization](https://arxiv.org/abs/2208.14286). [![](https://img.shields.io/github/stars/clevercool/ANT-Quantization?style=social&label=Code+Stars)](https://github.com/clevercool/ANT-Quantization) <span style="color:red">(2023 IEEE Micro Top Picks Honorable Mention)</span> 

- ``ICLR 2022`` **Cong Guo**, Yuxian Qiu, Jingwen Leng, Xiaotian Gao, Chen Zhang, Yunxin Liu, Fan Yang, Yuhao Zhu, Minyi Guo; [SQuant: On-the-Fly Data-Free Quantization via Diagonal Hessian Approximation](https://arxiv.org/abs/2202.07471). [![](https://img.shields.io/github/stars/clevercool/SQuant?style=social&label=Code+Stars)](https://github.com/clevercool/SQuant)
- ``ICCD 2022`` **Cong Guo**, Yuxian Qiu, Jingwen Leng, Chen Zhang, Ying Cao, Quanlu Zhang, Yunxin Liu, Fan Yang, Minyi Guo; [Nesting Forward Automatic Differentiation for Memory-Efficient Deep Neural Network Training](https://arxiv.org/abs/2209.10778). 
- ``MSN 2022`` Mustafa Tarik Sanic, **Cong Guo**, Jingwen Leng, Minyi Guo, Weiyin Ma;   [Towards Reliable AI Applications via Algorithm-Based Fault Tolerance on NVDLA](https://www.computer.org/csdl/proceedings-article/msn/2022/645700a736/1LUtObKmgko). <span style="color:red">(Best Paper Award)</span>  
- ``CF 2022`` Yangjie Zhou, Yaoxu Song, Jingwen Leng, Zihan Liu, Weihao Cui, Zhendong Zhang, **Cong Guo**, Quan Chen, Li Li, Minyi Guo;   [AdaptGear: Accelerating GNN Training via Adaptive Subgraph-Level Kernels on GPUs](https://arxiv.org/abs/2305.17408). 
- ``IISWC 2021`` Yangjie Zhou, Mengtian Yang, **Cong Guo**, Jingwen Leng, Yun Liang, Quan Chen, Minyi Guo, Yuhao Zhu; [Characterizing and Demystifying the Implicit Convolution Algorithm on Commercial Matrix-Multiplication Accelerators](https://arxiv.org/abs/2110.03901).
- ``ISCA 2021`` Yang Wang, Chen Zhang, Zhiqiang Xie, **Cong Guo**, Yunxin Liu, Jingwen Leng; [Dual-side Sparse Tensor Core](https://arxiv.org/abs/2105.09564), 
- ``SC 2020`` **Cong Guo**, Bo Yang Hsueh, Jingwen Leng, Yuxian Qiu, Yue Guan, Zehuan Wang, Xiaoying Jia, Xipeng Li, Minyi Guo, Yuhao Zhu; [Accelerating Sparse DNN Models without Hardware-Support via Tile-Wise Sparsity](https://arxiv.org/abs/2008.13006).  [![](https://img.shields.io/github/stars/clevercool/TileSparsity?style=social&label=Code+Stars)](https://github.com/clevercool/TileSparsity)
- ``DAC 2020``  **Cong Guo**, Yangjie Zhou, Jingwen Leng, Yuhao Zhu, Zidong Du, Quan Chen, Chao Li, Bin Yao, Minyi Guo; [Balancing Efficiency and Flexibility for DNN Acceleration via Temporal GPU-Systolic Array Integration](https://arxiv.org/abs/2002.08326).
- `CVPR 2019` Yuxian Qiu, Jingwen Leng, **Cong Guo**, Quan Chen, Chao Li, Minyi Guo, Yuhao Zhu; [Adversarial Defense Through Network Profiling Based Path Extraction](https://openaccess.thecvf.com/content_CVPR_2019/html/Qiu_Adversarial_Defense_Through_Network_Profiling_Based_Path_Extraction_CVPR_2019_paper.html). 

### Journal:
 
- ``IEEE Circuits and Systems Magazine 2025`` **Cong Guo**, Feng Cheng, Zhixu Du, James Kiessling, Jonathan Ku, Shiyu Li, Ziru Li, Mingyuan Ma, Tergel Molom-Ochir, Benjamin Morris, Haoxuan Shan, Jingwei Sun, Yitu Wang, Chiyue Wei, Xueying Wu, Yuhao Wu, Hao Frank Yang, Jingyang Zhang, Junyao Zhang, Qilin Zheng, Guanglei Zhou, Hai Li, Yiran Chen; [A Survey: Collaborative Hardware and Software Design in the Era of Large Language Models](https://ieeexplore.ieee.org/abstract/document/10876858). 
- ``IEEE Transactions on Computers 2025`` Chen Zhang, Yang Wang, Zhiqiang Xie, **Cong Guo**, Yunxin Liu, Jingwen Leng, Guangyu Sun, Zhigang Ji, Runsheng Wang, Yuan Xie, Ru Huang; [DSTC: Dual-Side Sparse Tensor Core for DNNs Acceleration on Modern GPU Architectures](https://ieeexplore.ieee.org/abstract/document/10709841).
- ``IEEE Transactions on Computers 2024``  **Cong Guo**, Fengchen Xue, Jingwen Leng, Yuxian Qiu, Yue Guan, Weihao Cui, Quan Chen, Minyi Guo; [Accelerating Sparse DNNs Based on Tiled GEMM](https://arxiv.org/abs/2402.10876).

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🏆 Honors and Awards
<!-- - *2024.05* [OlympusMons Awards 2023](https://e.huawei.com/en/topic/storage/olympus-mons-awards-2023) -->
- *2024.03* [Outstanding Doctoral Dissertation Award](https://www.gs.sjtu.edu.cn/yxbslw), Shanghai Jiao Tong University
- *2023.07* [IEEE Micro Top Picks from 2022 Computer Architecture Conferences Honorable Mention](https://www.computer.org/csdl/magazine/mi/2023/04/10167515/1OjMSZbXMas)
- *2023.06* Outstanding Doctoral Graduates, Shanghai Jiao Tong University
- *2022.08* Excellent Ph.D. Scholarship of Yang Yuanqing Education Fund (Top-3/500+), Shanghai Jiao Tong University
- *2020.11* Ph.D. National Scholarship (Top-8/500+), Ministry of Education, PRC
- *2020.07* DAC2020 Richard Newton Young Student Fellow, Design Automation Conference    
- *2018.11* VMware Scholarship, Shanghai Jiao Tong University
- *2017.11* National Second Prize, The 14th China Post-Graduate Mathematical Contest in Modeling

# 👔 Academic Service
Journal Reviewer:
 - IEEE Transactions on Computers (TC)
 - IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)
 - Science China Information Sciences (SCIS)
 - Transactions on Architecture and Code Optimization (TACO)
 - Transactions on Embedded Computing Systems (TECS)
 - IEEE Transactions on Very Large Scale Integration Systems (TVLSI)
 - IEEE Transactions on Circuits and Systems for Artificial Intelligence (TCASAI)

# 💻 Experience

- *2023.12 - Now*, Postdoctoral associate, Department of ECE, Duke University.
- *2021.06 - 2023.12*, Research intern, Shanghai Qi Zhi Institute.  
- *2023.04 - 2023.09*, Reaserch intern, ANT Group (AliPay).
- *2020.06 - 2021.05*, Research intern, Microsoft Research Asia (Beijing).  
- *2019.05 - 2019.12*, Intern, NVIDIA (Shanghai).
  
<!-- - Project 1: Design a Dual-side Sparse Tensor Core to support dual-side sparse matrix multiplication. Published in ISCA 2021.
- Project 2: Design a low-precision cache compression approach for accelerating DNN training and inference. Published in
ICCD 2022.
- Project 3: Design a new adaptive numerical data type for low-bit DNN quantization. Published in Micro 2022.
- Project 4: Design an on-the-fly data-free quantization method to significantly improve the model accuracy and accelerate the quantization processing. Published in ICLR 2022. -->
  
  
<!-- - Intern: NVIDIA (Shanghai) May 2019 - Dec. 2019
  - Design a structured sparse pruning method according to the characteristics of the neural network;
  - Efficiently implements the structured pruning method on the GPU Tensor Core to accelerate the inference stage of the neural network. Published in SC 2020. -->
  

# 📖 Educations
- *2020.09 - 2023.09*, Ph.D in Computer Science, Department of Computer Science and Engineering, Shanghai Jiao Tong University.
- *2017.09 - 2020.03*, M.E. in Computer Technology, Department of Computer Science and Engineering, Shanghai Jiao Tong University.
- *2012.09 - 2016.06*, B.S. in Computer Science, College of Computer Science and Software Engineering, Shenzhen University.


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->
