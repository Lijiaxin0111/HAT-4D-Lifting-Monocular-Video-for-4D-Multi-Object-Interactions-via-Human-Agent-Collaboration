<div align="center">

# HAT-4D

### Lifting Monocular Video for 4D Multi-Object Interactions via Human-Agent Collaboration

**ECCV 2026**

[![arXiv](https://img.shields.io/badge/arXiv-2606.28215-b31b1b.svg)](https://arxiv.org/pdf/2606.28215) [![Project Page](https://img.shields.io/badge/Project-HAT--4D-2b6cb0.svg)](https://lijiaxin0111.github.io/HAT4D/) [![Hugging Face Dataset](https://img.shields.io/badge/🤗%20Dataset-MVOIK--4D-yellow.svg)](https://huggingface.co/datasets/Lijiaxin0111/MVOIK-4D) [![Python](https://img.shields.io/badge/Python-3.10-blue.svg)](https://www.python.org/) [![PyTorch](https://img.shields.io/badge/PyTorch-2.1.0-ee4c2c.svg)](https://pytorch.org/) [![License](https://img.shields.io/badge/License-Apache--2.0-green.svg)](LICENSE)

</div>

<p align="center">
  <img src="asset/teaser_new.jpg" width="95%" alt="HAT-4D teaser">
</p>

## News 🔥

- **2026-06-30**: The **MVOIK-4D** dataset has been released on [Hugging Face](https://huggingface.co/datasets/Lijiaxin0111/MVOIK-4D).
- **2026-06-26**: HAT-4D is accepted to **ECCV 2026**.

## Overview ✨

HAT-4D is an agentic framework for reconstructing 3D geometry, temporal dynamics, and physical interactions of multiple objects from a single monocular video. The project targets dynamic, in-the-wild object interactions where severe occlusion, depth ambiguity, and complex motion make conventional monocular 4D reconstruction difficult.

By integrating vision-language models with a multi-level human-in-the-loop feedback mechanism, HAT-4D resolves interaction-induced ambiguities during 3D generation and 4D propagation. The framework further serves as a scalable data engine for **MVOIK-4D**, an open-world benchmark for monocular 4D interaction reconstruction with evaluation focused on physical plausibility and temporal consistency.

## Method 🧠

<p align="center">
  <img src="asset/method_pipeline.jpg" width="95%" alt="HAT-4D method pipeline">
</p>

HAT-4D decomposes monocular interaction lifting into agent-assisted perception, human feedback, 3D asset generation, and temporally consistent 4D propagation. This design enables the system to recover physically plausible multi-object interactions without relying on expensive multi-camera capture setups.



## ToDo List ✅

- [x] Open-source MVOIK-4D .
- [ ] Open-source HAT-4D toolkit.

## Citation 📝

If you find this project useful for your research, please cite:

```bibtex
@inproceedings{Li2026hat4d,
  title     = {HAT-4D: Lifting Monocular Video for 4D Multi-Object Interactions via Human-Agent Collaboration},
  author    = {Li, Jiaxin and Author, Second and Author, Third},
  booktitle = {Computer Vision -- ECCV 2026},
  year      = {2026},
  note      = {Accepted, to appear}
}
```

## References 🙏

We thank the following projects and systems for making this work possible:

- [SAM3D](https://github.com/facebookresearch/sam3d)
- [Qwen-VL](https://github.com/QwenLM/Qwen-VL)
- [viser](https://github.com/nerfstudio-project/viser)

## License 📄

This repository is released under the [Apache License 2.0](LICENSE).

Unless required by applicable law or agreed to in writing, software distributed under this license is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the [LICENSE](LICENSE) file for the full license text.
