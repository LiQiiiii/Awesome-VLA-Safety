<div align="center">

  <h2><b> Vision-Language-Action Safety: Threats, Challenges, Evaluations, and Mechanisms </b></h2>
  <h4> A unified and up-to-date overview of safety in Vision-Language-Action models </h4>

</div>

<div align="center">

<a href="这里填你的arXiv链接" target="_blank"><img src="https://img.shields.io/badge/arXiv-即将发布-009688.svg" alt="arXiv"></a>
![](https://img.shields.io/github/stars/LiQiiiii/Awesome-VLA-Safety?color=yellow)
![](https://img.shields.io/github/forks/LiQiiiii/Awesome-VLA-Safety?color=lightblue)
![](https://img.shields.io/github/last-commit/LiQiiiii/Awesome-VLA-Safety?color=green)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-blue)](https://github.com/LiQiiiii/Awesome-VLA-Safety/pulls)

</div>

This repository is for our paper:

> **[Vision-Language-Action Safety: Threats, Challenges, Evaluations, and Mechanisms](这里填你的PDF链接)** \
> [Bo Yin*](主页链接占位)<sup>1</sup>, [Qi Li*](主页链接占位)<sup>1</sup>, [Other Authors] \
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
  author={Yin, Bo and Li, Qi and others},
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

#### Visual Perturbations
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[Freezevla: Action-freezing attacks against vision-language-action models](https://arxiv.org/abs/2025) <br> Xin Wang, Jie Li, et al. |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/占位符v1.png"> |[Paper](https://arxiv.org/abs/2025)|

#### Physical Interventions
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[Phantom menace: Exploring and enhancing the robustness of vla models against physical sensor attacks](https://arxiv.org/abs/2026) <br> Xuancun Lu, Jiaxiang Chen, et al. |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/占位符v1.png"> |[Paper](https://arxiv.org/abs/2026)|


### Inference-Time Defenses

#### Decision-Layer Guardrails
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[Vlsa: Vision-language-action models with plug-and-play safety constraint layer](https://arxiv.org/abs/2025) <br> Songqiao Hu, Zeyi Liu, et al. |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/占位符v1.png"> |[Paper](https://arxiv.org/abs/2025)|

#### Runtime Monitoring
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[Failsafe: Reasoning and recovery from failures in vision-language-action models](https://arxiv.org/abs/2025) <br> Zijun Lin, Jiafei Duan, et al. |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/占位符v1.png"> |[Paper](https://arxiv.org/abs/2025)|

#### Physical Fail-safes
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[Towards safe robot foundation models using inductive biases](https://arxiv.org/abs/2025) <br> Maximilian Tölle, Theo Gruner, et al. |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/占位符v1.png"> |[Paper](https://arxiv.org/abs/2025)|


### Evaluation and Benchmarks
[🔝 Back to Top](#quick-links)

| Title & Authors | Introduction | Links |
|:--|  :----: | :---:|
|[Vla-risk: Benchmarking vision-language-action models with physical robustness](https://arxiv.org/abs/2025) <br> Yanchi Ru, Zhengyue Zhao, et al. |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/占位符v1.png"> |[Paper](https://arxiv.org/abs/2025)|
|[Vlatest: Testing and evaluating vision-language-action models for robotic manipulation](https://arxiv.org/abs/2025) <br> Zhijie Wang, Zhehua Zhou, et al. |<img width="1002" alt="image" src="https://paper-assets.alphaxiv.org/image/占位符v1.png"> |[Paper](https://arxiv.org/abs/2025)|
