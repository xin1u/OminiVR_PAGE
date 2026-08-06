<div align="center">

# 🎞️ OmniVR — Project Page

### Joint Video-Audio Conditional Generation for Restoring Degraded Historical Films

<a href="https://arxiv.org/abs/2608.04224"><img src="https://img.shields.io/badge/arXiv-Paper-red?logo=arxiv"></a> &nbsp;
<a href="https://xin1u.github.io/OminiVR_PAGE/"><img src="https://img.shields.io/badge/Project-Page-Green"></a> &nbsp;
<a href="https://github.com/xin1u/OminiVR"><img src="https://img.shields.io/badge/Code-GitHub-181717?logo=github"></a> &nbsp;
<a href="https://huggingface.co/xin1u/OmniVR"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Model%20%26%20Data-blue"></a> &nbsp;
<a href="http://creativecommons.org/licenses/by-sa/4.0/"><img src="https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg"></a>

**🌐 Live page: [xin1u.github.io/OminiVR_PAGE](https://xin1u.github.io/OminiVR_PAGE/)**

</div>

---

This repository hosts the **project page** for **OmniVR**, the first joint
audio-video generative restoration model for degraded historical films
([arXiv:2608.04224](https://arxiv.org/abs/2608.04224)).

The page is a single self-contained `index.html` (Tailwind CSS + vanilla JS,
no build step) featuring:

- 🎬 **Before ↔ After streaming comparisons** — drag the divider across the
  frame and A/B the soundtrack between the degraded input and the OmniVR
  restoration, with audio spectrograms for both.
- 🖼️ **Gallery** — 12 restored clips: 5 real historical film clips and
  7 speech / dialogue clips with lip-synced restored voice.
- 🌙 **Dark mode**, abstract, key contributions, and BibTeX.

```
OminiVR_PAGE/
├── index.html          # the entire page (self-contained)
└── real-films-demo/    # input/output video pairs + audio spectrograms
```

## 🖥️ Run Locally

No build step — just serve the folder:

```bash
git clone https://github.com/xin1u/OminiVR_PAGE.git
cd OminiVR_PAGE
python -m http.server 8000
# open http://localhost:8000
```

## 🔗 Resources

| | |
|---|---|
| 📄 Paper | [arXiv:2608.04224](https://arxiv.org/abs/2608.04224) · [HF Papers](https://huggingface.co/papers/2608.04224) |
| 💻 Code | [github.com/xin1u/OminiVR](https://github.com/xin1u/OminiVR) |
| 🤗 Weights, OmniVRBench & reference outputs | [huggingface.co/xin1u/OmniVR](https://huggingface.co/xin1u/OmniVR) |

## 📜 Citation

```bibtex
@article{lu2026omnivr,
  title={OmniVR: Joint Video-Audio Conditional Generation for Restoring Degraded Historical Films},
  author={Lu, Xin and Fan, Zihao and Zhong, Mingchen and Huang, Jie and Fu, Xueyang and Zha, Zheng-Jun},
  journal={arXiv preprint arXiv:2608.04224},
  year={2026}
}
```

## 📄 License

The website content is licensed under
[CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).
Layout inspired by the academic project-page ecosystem
(e.g. [Nerfies](https://nerfies.github.io/)).

---

<div align="center">

Please feel free to contact us if there is any question
(<a href="mailto:luxion@mail.ustc.edu.cn">luxion@mail.ustc.edu.cn</a>).

</div>
