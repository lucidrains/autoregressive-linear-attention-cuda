## Linear Attention - Autoregressive CUDA kernel (wip)

CUDA implementation of autoregressive linear attention, with all the latest research findings.

## Citations

```bibtex
@inproceedings{katharopoulos-et-al-2020,
    author    = {Katharopoulos, A. and Vyas, A. and Pappas, N. and Fleuret, F.},
    title     = {Transformers are RNNs: Fast Autoregressive Transformers with Linear Attention},
    booktitle = {Proceedings of the International Conference on Machine Learning (ICML)},
    year      = {2020},
    url       = {https://arxiv.org/abs/2006.16236}
}
```

```bibtex
@article{Nguyen2022MomentumTC,
    title   = {Momentum Transformer: Closing the Performance Gap Between Self-attention and Its Linearization},
    author  = {Tan Minh Nguyen and Richard Baraniuk and Robert M. Kirby and Stanley J. Osher and Bao Wang},
    journal = {ArXiv},
    year    = {2022},
    volume  = {abs/2208.00579}
}
```

```bibtex
@article{Zhai2021AnAF,
    title   = {An Attention Free Transformer}, // it is not really attention free, blatant clickbait. just linear attention with some gating added in
    author  = {Shuangfei Zhai and Walter A. Talbott and Nitish Srivastava and Chen Huang and Hanlin Goh and Ruixiang Zhang and Joshua M. Susskind},
    journal = {ArXiv},
    year    = {2021},
    volume  = {abs/2105.14103}
}
```
