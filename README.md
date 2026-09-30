# OmniVR project page

**OmniVR: Joint Audio-Video Conditional Generation for Archival Footage Restoration**

Xin Lu, Zihao Fan, Jie Huang, Mingchen Zhong, Hexin Zhang, Xueyang Fu, Zheng-Jun Zha

University of Science and Technology of China

[Live project page](https://xin1u.github.io/OminiVR_PAGE/) · [Latest manuscript, 30 September 2026](https://xin1u.github.io/OminiVR_PAGE/assets/OmniVR.pdf) · [arXiv](https://arxiv.org/abs/2608.04224) · [GitHub](https://github.com/xin1u/OminiVR) · [Hugging Face](https://huggingface.co/xin1u/OmniVR)

This repository hosts the project page, the supplied latest manuscript, and
the exact vector framework figure used in that manuscript. The page includes
updated author information, the abstract, a framework overview, links to both
Flash and multistep inference, and the existing audiovisual comparisons.

## Local serving

```bash
python -m http.server 8000
```

`index.html` uses Tailwind CSS and vanilla JavaScript with no build step.
The inference implementations are in the linked GitHub and Hugging Face
repositories. The paper reports an optimized Flash configuration; the
inference release documents its clip-window interface and current checkpoint
availability separately.

## Files

- `assets/OmniVR.pdf`: latest supplied manuscript, unchanged.
- `assets/architecture.pdf`: exact source of Figure 4 on page 6.
- `assets/architecture.png`: web rendering of that vector figure.
- `real-films-demo/`: existing input/output videos and spectrograms.

## Citation

```bibtex
@article{lu2026omnivr,
  title={OmniVR: Joint Audio-Video Conditional Generation for Archival Footage Restoration},
  author={Lu, Xin and Fan, Zihao and Huang, Jie and Zhong, Mingchen and Zhang, Hexin and Fu, Xueyang and Zha, Zheng-Jun},
  journal={arXiv preprint arXiv:2608.04224},
  year={2026},
  eprint={2608.04224},
  archivePrefix={arXiv},
  primaryClass={cs.CV},
  url={https://arxiv.org/abs/2608.04224}
}
```

The website content retains its existing [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) notice.
Contact: [luxion@mail.ustc.edu.cn](mailto:luxion@mail.ustc.edu.cn).
