# Awesome-Paper-List-for-Synthetic-Data-Generation
This repository aims to collect recent interested papers related to synthetic data generation, focusing on LLM post-training.

We divide synthetic data generation method into categories:

· [**Augmentation**](##Augmentation): 

· [**Iterative-Evolution**](##Iterative-Evolution): Method that contains iterative refinement of data or model.

· [**Distillation**](##Distillation): Method that distill intrinsic knowledge from models, may contain prompting/decoding/sampling strategy et.al. 

· [**External-Based**](##External-Based): Method that generate basing on external structure (tree/graph) or exterior searching.

· [**Environment**](##Enviroment): Method that contains curation and interaction with an external environment where certain approach of verification internally exists. e.g. code interpreter, bash, game .et.al.

· [**Hybrid**](##Hybrid): Mixture of above.

based on their algorithm. 

Other aspects includes:

· [**Filtering**](##Filtering)

| [[HOME PAGE]]() [[PDF]]()




## Interested Survey && Analysis

[**2024 Jul COLM**] [**Best Practices and Lessons Learned on Synthetic Data**](https://openreview.net/pdf?id=OJaWBhh61C), *Ruibo Liu, Jerry Wei, Fangyu Liu, Chenglei Si, Yanzhe Zhang, Jinmeng Rao, Steven Zheng, Daiyi Peng, Diyi Yang, Denny Zhou, Andrew M. Dai* 
[[HOME PAGE]](https://openreview.net/forum?id=OJaWBhh61C)

[**2024 Dec Arxiv**] [**Surveying the Effects of Quality, Diversity, and Complexity in Synthetic Data From Large Language Models**](https://arxiv.org/pdf/2412.02980v2), *Alex Havrilla, Andrew Dai, Laura O'Mahony, Koen Oostermeijer, Vera Zisler, Alon Albalak, Fabrizio Milo, Sharath Chandra Raparthy, Kanishk Gandhi, Baber Abbasi, Duy Phung, Maia Iyer, Dakota Mahan, Chase Blagden, Srishti Gureja, Mohammed Hamdy, Wen-Ding Li, Giovanni Paolini, Pawan Sasanka Ammanamanchi, Elliot Meyerson* 
[[HOME PAGE]](https://arxiv.org/abs/2412.02980v2) 



## Augmentation



## Iterative-Evolution
[**2024 ICLR poster**] [**WizardLM: Empowering Large Pre-Trained Language Models to Follow Complex Instructions**](https://arxiv.org/pdf/2304.12244), *Can Xu, Qingfeng Sun, Kai Zheng, Xiubo Geng, Pu Zhao, Jiazhan Feng, Chongyang Tao, Qingwei Lin, Daxin Jiang* | [[github]](https://github.com/nlpxucan/WizardLM) [[HOME PAGE]](https://proceedings.iclr.cc/paper_files/paper/2024/hash/82eec786fdfbbfa53450c5feb7d1ac92-Abstract-Conference.html)

[**2024 ICLR poster**] [**WizardCoder: Empowering Code Large Language Models with Evol-Instruct**](https://arxiv.org/pdf/2306.08568), *Ziyang Luo, Can Xu, Pu Zhao, Qingfeng Sun, Xiubo Geng, Wenxiang Hu, Chongyang Tao, Jing Ma, Qingwei Lin, Daxin Jiang* | [[github]](https://github.com/nlpxucan/WizardLM/tree/main/WizardCoder) [[HOME PAGE]](https://proceedings.iclr.cc/paper_files/paper/2024/hash/72eba29737f9c3a5a4ce8cdb7b667145-Abstract-Conference.html)

[**2025 ICLR Oral**] [**WizardMath: Empowering Mathematical Reasoning for Large Language Models via Reinforced Evol-Instruct**](https://arxiv.org/pdf/2308.09583), *Haipeng Luo, Qingfeng Sun, Can Xu, Pu Zhao, Jianguang Lou, Chongyang Tao, Xiubo Geng, Qingwei Lin, Shifeng Chen, Yansong Tang, Dongmei Zhang* | [[github]](https://github.com/nlpxucan/WizardLM/tree/main/WizardMath) [[HOME PAGE]](https://iclr.cc/virtual/2025/oral/31781)

[**2024 EMNLP**] [**Automatic Instruction Evolving for Large Language Models**](https://arxiv.org/pdf/2406.00770), *Weihao Zeng, Can Xu, Yingxiu Zhao, Jian-Guang Lou, Weizhu Chen* | [[github]]( ) [[HOME PAGE]](https://aclanthology.org/2024.emnlp-main.397/)

[**2024 ICLR Oral**] [**Self-Alignment with Instruction Backtranslation**](https://proceedings.iclr.cc/paper_files/paper/2024/file/0f8e3534eb8dee7478d4dc0e9d9a0b1a-Paper-Conference.pdf), *Xian Li, Ping Yu, Chunting Zhou, Timo Schick, Omer Levy, Luke Zettlemoyer, Jason E Weston, Mike Lewis* | [[HOME PAGE]](https://proceedings.iclr.cc/paper_files/paper/2024/hash/0f8e3534eb8dee7478d4dc0e9d9a0b1a-Abstract-Conference.html)

[**2024 ICML poster**] [**SPIN: Self-Play Fine-Tuning Converts Weak Language Models to Strong Language Models**](https://arxiv.org/pdf/2401.01335), *Zixiang Chen, Yihe Deng, Huizhuo Yuan, Kaixuan Ji, Quanquan Gu* | [[github]](https://github.com/uclaml/SPIN) [[HOME PAGE]](https://icml.cc/virtual/2024/poster/34179)

## Distillation

[**2023 MATH-AI poster**] [**TinyGSM: achieving > 80% on GSM8k with small language models**](https://arxiv.org/pdf/2312.09241), *Bingbin Liu, Sebastien Bubeck, Ronen Eldan, Janardhan Kulkarni, Yuanzhi Li, Anh Nguyen, Rachel Ward, Yi Zhang* | [[Hugging Face]](https://huggingface.co/papers/2312.09241) [[HOME PAGE]](https://neurips.cc/virtual/2023/74985)

[**2024 ICLR poster**] [**RLCD: Reinforcement Learning from Contrastive Distillation for Language Model Alignment**](https://arxiv.org/pdf/2307.12950), *Kevin Yang, Dan Klein, Asli Celikyilmaz, Nanyun (Violet) Peng, Yuandong Tian* | [[github]](https://github.com/facebookresearch/RLCD) [[HOME PAGE]](https://proceedings.iclr.cc/paper_files/paper/2024/hash/5bd09a559a8c8e230697107b0f353d39-Abstract-Conference.html)

[**2024 ICLR poster**] [**West-of-N: Synthetic Preferences for Self-Improving Reward Models**](https://arxiv.org/pdf/2401.12086), *Alizée Pace, Jonathan Mallinson, Eric Malmi, Sebastian Krause, Aliaksei Severyn* | [[HOME PAGE]](https://iclr.cc/virtual/2024/22444)

[**2023 ACL**] [**Self-Instruct: Aligning Language Models with Self-Generated Instructions**](https://aclanthology.org/2023.acl-long.754.pdf), *Yizhong Wang, Yeganeh Kordi, Swaroop Mishra, Alisa Liu, Noah A. Smith, Daniel Khashabi, Hannaneh Hajishirzi* | [[github]](https://github.com/yizhongw/self-instruct) [[HOME PAGE]](https://aclanthology.org/2023.acl-long.754/)

[**2023 ICLR**] [**#InsTag: Instruction Tagging for Analyzing Supervised Fine-tuning of Large Language Models**](https://proceedings.iclr.cc/paper_files/paper/2024/file/9dae2a90bae49dc874ce1ca8fcc20879-Paper-Conference.pdf), *Keming Lu, Hongyi Yuan, Zheng Yuan, Runji Lin, Junyang Lin, Chuanqi Tan, Chang Zhou, Jingren Zhou* | [[github]](https://github.com/OFA-Sys/InsTag) [[HOME PAGE]](https://proceedings.iclr.cc/paper_files/paper/2024/hash/9dae2a90bae49dc874ce1ca8fcc20879-Abstract-Conference.html)




## External-Based

[**2024 NeurIPS**] [**Toward Self-Improvement of LLMs via Imagination, Searching, and Criticizing**](https://proceedings.neurips.cc/paper_files/paper/2024/file/5e5853f35164e434015716a8c2a66543-Paper-Conference.pdf), *Ye Tian, Baolin Peng, Linfeng Song, Lifeng Jin, Dian Yu, Haitao Mi, Dong Yu* | [[github]](https://github.com/YeTianJHU/AlphaLLM) [[HOME PAGE]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/5e5853f35164e434015716a8c2a66543-Abstract-Conference.html)



## Environment
[**2023 May ACM Computing Survey**] [**Tool Learning with Foundation Models**](https://dl.acm.org/doi/pdf/10.1145/3704435), *Yujia Qin, Shengding Hu, Yankai Lin, Weize Chen, Ning Ding, Ganqu Cui, Zheni Zeng, Yufei Huang, Chaojun Xiao, Chi Han, Yi Ren Fung, Yusheng Su, Huadong Wang, Cheng Qian, Runchu Tian, Kunlun Zhu, Shihao Liang, Xingyu Shen, Bokai Xu, Zhen Zhang, Yining Ye, Bowen Li, Ziwei Tang, Jing Yi, Yuzhang Zhu, Zhenning Dai, Lan Yan, Xin Cong, Yaxi Lu, Weilin Zhao, Yuxiang Huang, Junxi Yan, Xu Han, Xian Sun, Dahai Li, Jason Phang, Cheng Yang, Tongshuang Wu, Heng Ji, Zhiyuan Liu, Maosong Sun* | [[github]](https://github.com/OpenBMB/BMTools) [[HOME PAGE]](https://dl.acm.org/doi/10.1145/3704435)

[**2024 ICLR Spotlight**] [**ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs**](https://arxiv.org/pdf/2307.16789), *Yujia Qin, Shihao Liang, Yining Ye, Kunlun Zhu, Lan Yan, Yaxi Lu, Yankai Lin, Xin Cong, Xiangru Tang, Bill Qian, Sihan Zhao, Lauren Hong, Runchu Tian, Ruobing Xie, Jie Zhou, Mark Gerstein, dahai li, Zhiyuan Liu, Maosong Sun* | [[github]](https://github.com/OpenBMB/ToolBench) [[HOME PAGE]](https://proceedings.iclr.cc/paper_files/paper/2024/hash/28e50ee5b72e90b50e7196fde8ea260e-Abstract-Conference.html) 



## Hybrid

[**2024 NeurIPS**] **Distill+Enviroment**：[**OpenMathInstruct-1: A 1.8 Million Math Instruction Tuning Dataset**](https://proceedings.neurips.cc/paper_files/paper/2024/file/3d5aa9a7ce28cdc710fbd044fd3610f3-Paper-Datasets_and_Benchmarks_Track.pdf), *Shubham Toshniwal, Ivan Moshkov, Sean Narenthiran, Daria Gitman, Fei Jia, Igor Gitman* | [[Hugging Face]](https://huggingface.co/datasets/nvidia/OpenMathInstruct-1) [[HOME PAGE]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/3d5aa9a7ce28cdc710fbd044fd3610f3-Abstract-Datasets_and_Benchmarks_Track.html) 

[**2024 ACL**] **External Retrieve+Augmentation**：[**Better Synthetic Data by Retrieving and Transforming Existing Datasets**](https://aclanthology.org/2024.findings-acl.385.pdf), *Saumya Gandhi, Ritu Gala, Vijay Viswanathan, Tongshuang Wu, Graham Neubig* | [[HOME PAGE]](https://aclanthology.org/2024.findings-acl.385/) 

## Filtering

[**2024 NAACL**] [**From Quantity to Quality: Boosting LLM Performance with Self-Guided Data Selection for Instruction Tuning**](https://arxiv.org/pdf/2308.12032), *Ming Li, Yong Zhang, Zhitao Li, Jiuhai Chen, Lichang Chen, Ning Cheng, Jianzong Wang, Tianyi Zhou, Jing Xiao* | [[github]](https://github.com/tianyi-lab/Cherry_LLM) [[HOME PAGE]](https://aclanthology.org/2024.naacl-long.421/) 

[**2024 ICLR poster**] [**AlpaGasus: Training a Better Alpaca with Fewer Data**](https://openreview.net/pdf?id=FdVXgSJhvz), *Lichang Chen, Shiyang Li, Jun Yan, Hai Wang, Kalpa Gunaratna, Vikas Yadav, Zheng Tang, Vijay Srinivasan, Tianyi Zhou, Heng Huang, Hongxia Jin* | [[github]](https://github.com/Lichang-Chen/AlpaGasus) [[HOME PAGE]](https://openreview.net/forum?id=FdVXgSJhvz) 
