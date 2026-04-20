<div align="center">

  <h2><b> Vision-Language-Action Safety: Threats, Challenges, Evaluations, and Mechanisms </b></h2>
  <h4> A unified and up-to-date overview of safety in Vision-Language-Action models </h4>

</div>

<div align="center">

<a href="arXiv链接" target="_blank"><img src="https://img.shields.io/badge/arXiv-即将发布-009688.svg" alt="arXiv"></a>
![](https://img.shields.io/github/stars/LiQiiiii/Awesome-VLA-Safety?color=yellow)
![](https://img.shields.io/github/forks/LiQiiiii/Awesome-VLA-Safety?color=lightblue)
![](https://img.shields.io/github/last-commit/LiQiiiii/Awesome-VLA-Safety?color=green)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-blue)](https://github.com/LiQiiiii/Awesome-VLA-Safety/pulls)

</div>

This repository is for our paper:

> **[Vision-Language-Action Safety: Threats, Challenges, Evaluations, and Mechanisms](PDF链接)** \
> [****](主页链接占位)<sup>1</sup>, [*****](主页链接占位)<sup>1</sup>, [Other Authors] \
> <sup>1</sup>National University of Singapore \
> <sup>*</sup>Equal contribution. \
> <sup>§</sup>Project Lead & Corresponding Author: yin.bo@u.nus.edu, liqi@u.nus.edu

<p align="center">
  <img src="assets/figure1.png" alt="Timeline" style="max-width:100%;" /><br />
  <strong>Figure 1. Development timeline of representative VLA capability models and VLA safety research.</strong>
</p>

<p align="center">
  <img src="assets/figure2.png" alt="Taxonomy" style="max-width:100%;" /><br />
  <strong>Figure 2. An overview of the VLA safety landscape covered in this survey.</strong>
</p>

## Citation
```bibtex
@article{vlasafety2026,
  title={Vision-Language-Action Safety: Threats, Challenges, Evaluations, and Mechanisms},
  author={name},
  journal={arXiv preprint arXiv:xxxx.xxxxx},
  year={2026}
}
```

---
> 🌟 If you find this resource helpful, please consider to star this repository and cite our [work](#citation)!
> 
> 🙋 Please let us know if you find out a mistake or have any suggestions!
> 
> **To add new papers or models**
>
> Should you identify any related work that has not been included, please feel free to notify us via Github PR or email: yin.bo@u.nus.edu, liqi@u.nus.edu. We will add your paper to the list as soon as possible.

---
<p align="center">
<img src="assets/taxonomy.png" width = "95%" alt="Taxonomy Image" align=center />
</p>

### Quick Links

- [Training-Time Attacks](#training-time-attacks)
  - [Input-Centric Backdoors](#input-centric-backdoors)
  - [Temporal and State-Space Backdoors](#temporal-and-state-space-backdoors)
- [Training-Time Defenses](#training-time-defenses)
  - [Data, Perception, and Reward-Centric Alignment](#data-perception-and-reward-centric-alignment)
  - [Policy-Centric Safety Optimization](#policy-centric-safety-optimization)
  - [Human-in-the-Loop Policy Refinement](#human-in-the-loop-policy-refinement)
- [Inference-Time Attacks](#inference-time-attacks)
  - [Semantic Jailbreaks](#semantic-jailbreaks)
  - [Visual Perturbations](#visual-perturbations)
  - [Physical Interventions](#physical-interventions)
- [Inference-Time Defenses](#inference-time-defenses)
  - [Decision-Layer Guardrails](#decision-layer-guardrails)
  - [Runtime Monitoring](#runtime-monitoring)
  - [Physical Fail-safes](#physical-fail-safes)
- [Evaluation and Benchmarks](#evaluation-and-benchmarks)
  - [Multi-Level Benchmarks](#multi-level-benchmarks)
  - [Uncertainty Calibration](#uncertainty-calibration)

### Training-Time Attacks

#### Input-Centric Backdoors
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[DropVLA: An action-level backdoor attack on vision-language-action models](https://arxiv.org/abs/2026) <br> Zonghuan Xu, Jiayu Li, et al. |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/占位符v1.png"> |[Paper](https://arxiv.org/abs/2026)|

#### Temporal and State-Space Backdoors
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[SilentDrift: Exploiting action chunking for stealthy backdoor attacks on vision-language-action models](https://arxiv.org/abs/2026) <br> Bingxin Xu, Yuzhang Shang, et al. |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/占位符v1.png"> |[Paper](https://arxiv.org/abs/2026)|


### Training-Time Defenses

#### Data, Perception, and Reward-Centric Alignment
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[EvoVLA: Self-evolving vision-language-action model](https://arxiv.org/abs/2025) <br> Zeting Liu, Zida Yang, et al. |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/占位符v1.png"> |[Paper](https://arxiv.org/abs/2025)|

#### Policy-Centric Safety Optimization
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[SafeVLA: Towards safety alignment of vision-language-action model via constrained learning](https://arxiv.org/abs/2025) <br> Borong Zhang, Yuhao Zhang, et al. |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/占位符v1.png"> |[Paper](https://arxiv.org/abs/2025)|

#### Human-in-the-Loop Policy Refinement
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[Human-assisted robotic policy refinement via action preference optimization](https://arxiv.org/abs/2025) <br> Wenke Xia, Yichu Yang, et al. |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/占位符v1.png"> |[Paper](https://arxiv.org/abs/2025)|


### Inference-Time Attacks

#### Semantic Jailbreaks
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[Jailbreaking llm-controlled robots](https://arxiv.org/pdf/2410.13691) <br> Robey, Alexander and Ravichandran, Zachary and Kumar, Vijay and Hassani, Hamed and Pappas, George J |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2410.13691v2.png"> |[Paper](https://arxiv.org/pdf/2410.13691)|[//]: #04/19
|[![Star](https://img.shields.io/github/stars/embodied-llms-safety.github.io/.svg?style=social&label=Star)](https://github.com/embodied-llms-safety.github.io/)<br>[Badrobot: Jailbreaking embodied llms in the physical world](https://arxiv.org/pdf/2407.20242) <br> Zhang, Hangtao and Zhu, Chenyu and Wang, Xianlong and Zhou, Ziqi and Yin, Changgan and Li, Minghui and Xue, Lulu and Wang, Yichen and Hu, Shengshan and Liu, Aishan and others |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2407.20242v4.png"> |[Github](https://embodied-llms-safety.github.io/) <br> [Paper](https://arxiv.org/pdf/2407.20242)|[//]: #04/19
|[![Star](https://img.shields.io/github/stars/eliotjones1/robogcg.svg?style=social&label=Star)](https://github.com/eliotjones1/robogcg)<br>[Adversarial attacks on robotic vision language action models](https://arxiv.org/pdf/2506.03350) <br> Jones, Eliot Krzysztof and Robey, Alexander and Zou, Andy and Ravichandran, Zachary and Pappas, George J and Hassani, Hamed and Fredrikson, Matt and Kolter, J Zico |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2506.03350v1.png"> |[Github](https://github.com/eliotjones1/robogcg) <br> [Paper](https://arxiv.org/pdf/2506.03350)|[//]: #04/19
|[![Star](https://img.shields.io/github/stars/verazuo/jailbreak_llms.svg?style=social&label=Star)](https://github.com/verazuo/jailbreak_llms)<br>["do anything now": Characterizing and evaluating in-the-wild jailbreak prompts on large language models](https://arxiv.org/pdf/2308.03825) <br> Shen, Xinyue and Chen, Zeyuan and Backes, Michael and Shen, Yun and Zhang, Yang |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2308.03825v2.png"> |[Github](https://github.com/verazuo/jailbreak_llms) <br> [Paper](https://arxiv.org/pdf/2308.03825)|[//]: #04/19


#### Visual Perturbations
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[![Star](https://img.shields.io/github/stars/William-wAng618/roboticAttack.svg?style=social&label=Star)](https://github.com/William-wAng618/roboticAttack)<br>[Exploring the adversarial vulnerabilities of vision-language-action models in robotics](https://arxiv.org/pdf/2411.13587) <br> Wang, Taowen and Han, Cheng and Liang, James and Yang, Wenhao and Liu, Dongfang and Zhang, Luna Xinyu and Wang, Qifan and Luo, Jiebo and Tang, Ruixiang |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2411.13587v4.png"> |[Github](https://github.com/William-wAng618/roboticAttack) <br> [Paper](https://arxiv.org/pdf/2411.13587)|[//]: #04/19
|[When alignment fails: Multimodal adversarial attacks on vision-language-action models](https://arxiv.org/abs/2511.16203) <br> Yan, Yuping and Xie, Yuhan and Zhang, Yixin and Lyu, Lingjuan and Wang, Handing and Jin, Yaochu |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2411.13587v4.png"> |[Paper](https://arxiv.org/abs/2511.16203)|[//]: #04/19
|[![Star](https://img.shields.io/github/stars/xinwong/FreezeVLA.svg?style=social&label=Star)](https://github.com/xinwong/FreezeVLA)<br>[Freezevla: Action-freezing attacks against vision-language-action models](https://arxiv.org/abs/2509.19870) <br> Wang, Xin and Li, Jie and Weng, Zejia and Wang, Yixu and Gao, Yifeng and Pang, Tianyu and Du, Chao and Teng, Yan and Wang, Yingchun and Wu, Zuxuan and others |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2509.19870v1.png"> |[Github](https://github.com/xinwong/FreezeVLA) <br> [Paper](https://arxiv.org/abs/2509.19870)|[//]: #04/19


#### Physical Interventions
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[Phantom menace: Exploring and enhancing the robustness of vla models against physical sensor attacks](https://arxiv.org/abs/2511.10008) <br> Lu, Xuancun and Chen, Jiaxiang and Xiao, Shilin and Jin, Zizhi and Chen, Zhangrui and Yu, Hanwen and Qian, Bohan and Zhou, Ruochen and Ji, Xiaoyu and Xu, Wenyuan |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2511.10008v2.png"> |[Paper](https://arxiv.org/abs/2511.10008)|[//]: #04/19
|[State Backdoor: Towards Stealthy Real-world Poisoning Attack on Vision-Language-Action Model in State Space](https://arxiv.org/abs/2601.04266) <br> Ji Guo, Wenbo Jiang, Yansong Lin, Yijing Liu, Ruichen Zhang, Guomin Lu, Aiguo Chen, Xinshuo Han, Hongwei Li, Dusit Niyato |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2601.04266v1.png"> |[Paper](https://arxiv.org/abs/2601.04266)|[//]: #04/19


### Inference-Time Defenses

#### Decision-Layer Guardrails
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[![Star](https://img.shields.io/github/stars/THU-RCSCT/vlsa-aegis.svg?style=social&label=Star)](https://github.com/THU-RCSCT/vlsa-aegis)<br>[VLSA: Vision-Language-Action Models with Plug-and-Play Safety Constraint Layer](https://arxiv.org/abs/2512.11891) <br> Hu, Songqiao and Liu, Zeyi and Liu, Shuang and Cen, Jun and Meng, Zihan and He, Xiao |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2512.11891v1.png"> |[Github](https://github.com/THU-RCSCT/vlsa-aegis) <br> [Paper](https://arxiv.org/abs/2512.11891)|[//]: #04/19
|[Safety guardrails for llm-enabled robots](https://arxiv.org/pdf/2503.07885) <br> Zachary Ravichandran, Alexander Robey, Vijay Kumar, George J. Pappas, Hamed Hassani |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2503.07885v2.png"> |[Paper](https://arxiv.org/pdf/2503.07885)|[//]: #04/19
|[From Words to Safety: Language-Conditioned Safety Filtering for Robot Navigation](https://arxiv.org/abs/2511.05889) <br> Zeyuan Feng, Haimingyue Zhang, Somil Bansal |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2511.05889v1.png"> |[Paper](https://arxiv.org/abs/2511.05889)|[//]: #04/20


#### Runtime Monitoring
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[Run-time observation interventions make vision-language-action models more visually robust](https://arxiv.org/abs/2410.01971) <br> Asher J. Hancock, Allen Z. Ren, Anirudha Majumdar |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2410.01971v1.png"> |[Paper](https://arxiv.org/abs/2410.01971)|[//]: #04/20
|[Safe-vln: Collision avoidance for vision-and-language navigation of autonomous robots operating in continuous environments](https://arxiv.org/pdf/2311.02817) <br> Lu Yue, Dongliang Zhou, Liang Xie, Feitian Zhang, Ye Yan, Erwei Yin |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2311.02817v2.png"> |[Paper](https://arxiv.org/pdf/2311.02817)|[//]: #04/20
|[Affordance Field Intervention: Enabling VLAs to Escape Memory Traps in Robotic Manipulation](https://arxiv.org/pdf/2512.07472) <br> Siyu Xu, Zijian Wang, Yunke Wang, Chenghao Xia, Tao Huang, Chang Xu |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2512.07472v1.png"> |[Paper](https://arxiv.org/pdf/2512.07472)|[//]: #04/20
|[![Star](https://img.shields.io/github/stars/real-stanford/reflect.svg?style=social&label=Star)](https://github.com/real-stanford/reflect)<br>[Reflect: Summarizing robot experiences for failure explanation and correction](https://arxiv.org/abs/2306.15724) <br> Zeyi Liu, Arpit Bahety, Shuran Song |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2306.15724v4.png"> |[Github](https://github.com/real-stanford/reflect) <br> [Paper](https://arxiv.org/abs/2306.15724)|[//]: #04/20
|[Failsafe: Reasoning and recovery from failures in vision-language-action models](https://arxiv.org/abs/2510.01642) <br> Zijun Lin, Jiafei Duan, Haoquan Fang, Dieter Fox, Ranjay Krishna, Cheston Tan, Bihan Wen |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2510.01642v2.png"> |[Paper](https://arxiv.org/abs/2510.01642)|[//]: #04/20

#### Physical Fail-safes
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[Towards safe robot foundation models using inductive biases](https://arxiv.org/abs/2505.10219) <br> Maximilian Tölle, Theo Gruner, Daniel Palenicek, Tim Schneider, Jonas Günster, Joe Watson, Davide Tateo, Puze Liu, Jan Peters |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2505.10219v1.png"> |[Paper](https://arxiv.org/abs/2505.10219)|[//]: #04/20
|[DroneVLA: VLA based Aerial Manipulation](https://arxiv.org/abs/2601.13809) <br> Fawad Mehboob, Monijesu James, Amir Habel, Jeffrin Sam, Miguel Altamirano Cabrera, Dzmitry Tsetserukou |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2601.13809v2.png"> |[Paper](https://arxiv.org/abs/2601.13809)|[//]: #04/20
|[CompliantVLA-adaptor: VLM-Guided Variable Impedance Action for Safe Contact-Rich Manipulation](https://arxiv.org/abs/2601.15541) <br> Heng Zhang, Wei-Hsing Huang, Qiyi Tong, Gokhan Solak, Puze Liu, Kaidi Zhang, Sheng Liu, Jan Peters, Yu She, Arash Ajoudani |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2601.15541v2.png"> |[Paper](https://arxiv.org/abs/2601.15541)|[//]: #04/20


### Evaluation and Benchmarks

#### Multi-Level Benchmarks
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[VLA-Arena: An Open-Source Framework for Benchmarking Vision-Language-Action Models](https://arxiv.org/abs/2512.22539) <br> Borong Zhang, Jiahao Li, Jiachen Shen, Yishuai Cai, Yuhao Zhang, Yuanpei Chen, Juntao Dai, Jiaming Ji, Yaodong Yang |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2512.22539v1.png"> |[Paper](https://arxiv.org/abs/2512.22539)|[//]: #04/20
|[Generating robot constitutions \& benchmarks for semantic safety](https://arxiv.org/abs/2503.08663) <br> Pierre Sermanet, Anirudha Majumdar, Alex Irpan, Dmitry Kalashnikov, Vikas Sindhwani |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2503.08663v1.png"> |[Paper](https://arxiv.org/abs/2503.08663)|[//]: #04/20
|[Can Vision-Language Models Understand Construction Workers? An Exploratory Study](https://arxiv.org/abs/2601.10835) <br> Hieu Bui, Nathaniel E. Chodosh, Arash Tavakoli |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2601.10835v1.png"> |[Paper](https://arxiv.org/abs/2601.10835)|[//]: #04/20

#### Uncertainty Calibration
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[Vlatest: Testing and evaluating vision-language-action models for robotic manipulation](https://arxiv.org/abs/2409.12894) <br> Zhijie Wang, Zhehua Zhou, Jiayang Song, Yuheng Huang, Zhan Shu, Lei Ma |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2409.12894v2.png"> |[Paper](https://arxiv.org/abs/2409.12894)|[//]: #04/20
|[ROVER: Regulator-Driven Robust Temporal Verification of Black-Box Robot Policies](https://arxiv.org/abs/2511.17781) <br> Kristy Sakano, Jianyu An, Dinesh Manocha, Huan Xu |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2511.17781v2.png"> |[Paper](https://arxiv.org/abs/2511.17781)|[//]: #04/20
|[![Star](https://img.shields.io/github/stars/vla-safe/SAFE.svg?style=social&label=Star)](https://github.com/vla-safe/SAFE)<br>[Safe: Multitask failure detection for vision-language-action models](https://arxiv.org/abs/2506.09937) <br> Qiao Gu, Yuanliang Ju, Shengxiang Sun, Igor Gilitschenski, Haruki Nishimura, Masha Itkina, Florian Shkurti |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2506.09937v2.png"> |[Github](https://github.com/vla-safe/SAFE) <br> [Paper](https://arxiv.org/abs/2506.09937)|[//]: #04/20
|[Confidence calibration in vision-language-action models](https://arxiv.org/abs/2507.17383) <br> Thomas P Zollo, Richard Zemel |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2507.17383v2.png"> |[Paper](https://arxiv.org/abs/2507.17383)|[//]: #04/20
|[Evaluating uncertainty and quality of visual language action-enabled robots](https://arxiv.org/abs/2507.17049) <br> Pablo Valle, Chengjie Lu, Shaukat Ali, Aitor Arrieta |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/2507.17049v2.png"> |[Paper](https://arxiv.org/abs/2507.17049)|[//]: #04/20
