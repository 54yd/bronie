# ShowUI
<p align="center">
<img src="assets/showui.jpg" alt="ShowUI" width="480">
<p>

<p align="center">
        🤗 <a href="https://huggingface.co/showlab/ShowUI-2B">Hugging Models</a>&nbsp&nbsp 
        | &nbsp&nbsp 📑 <a href="https://arxiv.org/abs/2411.17465">Paper</a> &nbsp&nbsp 
        | &nbsp&nbsp 🤗 <a href="https://huggingface.co/spaces/showlab/ShowUI">Spaces Demo</a> &nbsp&nbsp 
        | &nbsp&nbsp 🕹️ <a href="https://openbayes.com/console/public/tutorials/I8euxlahBAm">OpenBayes贝式计算</a> &nbsp&nbsp </a> 
<br>
🤗 <a href="https://huggingface.co/datasets/showlab/ShowUI-desktop-8K">Datasets</a>&nbsp&nbsp | &nbsp&nbsp💬 <a href="https://x.com/_akhaliq/status/1864387028856537400">X (Twitter)</a>&nbsp&nbsp
| &nbsp&nbsp 🖥️ <a href="https://github.com/showlab/computer_use_ootb">Computer Use</a> &nbsp&nbsp </a> 
|  &nbsp&nbsp 📖 <a href="https://github.com/showlab/Awesome-GUI-Agent">GUI Paper List</a> &nbsp&nbsp </a>
</p>

<!-- [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fshowlab%2FShowUI&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com) -->

> [**ShowUI: One Vision-Language-Action Model for GUI Visual Agent**](https://arxiv.org/abs/2411.17465)<br>
> [Kevin Qinghong Lin](https://qinghonglin.github.io/), [Linjie Li](https://scholar.google.com/citations?user=WR875gYAAAAJ&hl=en), [Difei Gao](https://scholar.google.com/citations?user=WR875gYAAAAJ&hl=en), [Zhengyuan Yang](https://zyang-ur.github.io/), [Shiwei Wu](https://scholar.google.com/citations?user=qWOFgUcAAAAJ), [Zechen Bai](https://www.baizechen.site/), [Weixian Lei](), [Lijuan Wang](https://scholar.google.com/citations?user=cDcWXuIAAAAJ&hl=en), [Mike Zheng Shou](https://scholar.google.com/citations?user=h1-3lSoAAAAJ&hl=en)
> <br>Show Lab @ National University of Singapore, Microsoft<br>

## 🔥 Update
- [x] [2024.12.23] Update `showui` for UI-guided token selection implementation.
- [x] [2024.12.15] ShowUI received **Outstanding Paper Award** at [NeurIPS2024 Open-World Agents workshop](https://sites.google.com/view/open-world-agents/schedule).
- [x] [2024.12.9] Support int8 Quantization.
- [x] **[2024.12.5] Major Update: ShowUI is integrated into [OOTB](https://github.com/showlab/computer_use_ootb?tab=readme-ov-file) for local run!**
- [x] [2024.12.1] We support iterative refinement to improve grounding accuracy. Try it at [HF Spaces demo](https://huggingface.co/spaces/showlab/ShowUI).
- [x] [2024.11.27] We release the [arXiv paper](https://arxiv.org/abs/2411.17465), [HF Spaces demo](https://huggingface.co/spaces/showlab/ShowUI) and [`ShowUI-desktop-8K`](https://huggingface.co/datasets/showlab/ShowUI-desktop-8K).
- [x] [2024.11.16] [`showlab/ShowUI-2B`](https://huggingface.co/showlab/ShowUI-2B) is available at huggingface.

## 🖥️ Computer Use
See [Computer Use OOTB](https://github.com/showlab/computer_use_ootb?tab=readme-ov-file) for using ShowUI to control your PC.

https://github.com/user-attachments/assets/f50b7611-2350-4712-af9e-3d31e30020ee

## 🚀 Training
Our Training codebases supports:
- [x] DeepSpeed Zero1, Zero2, Zero3
- [x] Full-tuning (FP32, FP16, BF16), LoRA, QLoRA
- [x] SDPA, Flash Attention 2
- [x] Multiple datasets mixed training
- [x] Interleaved data streaming

See [Train](TRAIN.md) for training set up.

## 🕹️ UI-Guided Token Selection
Try `test.ipynb`, which seamless support for Qwen2VL models.

<div style="display: flex; justify-content: space-between;">
  <img src="examples/chrome.png" alt="(a) Screenshot patch number: 1296" style="width: 48%;"/>
  <img src="examples/demo.png" alt="(b) By applying UI-graph, UI Component number: 167" style="width: 48%;"/>
</div>

## ⭐ Quick Start
See [Quick Start](QUICK_START.md) for model usage.

## 🤗 Local Gradio
See [Gradio](GRADIO.md) for installation.


## BibTeX
If you find our work helpful, please consider citing our paper.

```
@misc{lin2024showui,
      title={ShowUI: One Vision-Language-Action Model for GUI Visual Agent}, 
      author={Kevin Qinghong Lin and Linjie Li and Difei Gao and Zhengyuan Yang and Shiwei Wu and Zechen Bai and Weixian Lei and Lijuan Wang and Mike Zheng Shou},
      year={2024},
      eprint={2411.17465},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2411.17465}, 
}
```
