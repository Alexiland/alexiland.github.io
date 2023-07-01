---
title: "CPT: Efficient Deep Neural Network Training via Cyclic Precision
"
collection: publications
permalink: /publication/pub1
excerpt: 'Low-precision deep neural network (DNN) training has gained tremendous attention as reducing precision is one of the most effective knobs for boosting DNNs training time/energy efficiency. In this paper, we attempt to explore low-precision training from a new perspective as inspired by recent findings in understanding DNN training: we conjecture that DNNs' precision might have a similar effect as the learning rate during DNN training, and advocate dynamic precision along the training trajectory for further boosting the time/energy efficiency of DNN training. Specifically, we propose Cyclic Precision Training (CPT) to cyclically vary the precision between two boundary values which can be identified using a simple precision range test within the first few training epochs. Extensive simulations and ablation studies on five datasets and eleven models demonstrate that CPT's effectiveness is consistent across various models/tasks (including classification and language modeling). Furthermore, through experiments and visualization we show that CPT helps to (1) converge to a wider minima with a lower generalization error and (2) reduce training variance which we believe opens up a new design knob for simultaneously improving the optimization and efficiency of DNN training.'
date: 2021-5-7
venue: 'ICLR2021'
paperurl: 'https://arxiv.org/abs/2101.09868'
citation: 'Fu, Y., Guo, H., Li, M., Yang, X., Ding, Y., Chandra, V., & Lin, Y. (2021). CPT: Efficient deep neural network training via cyclic precision. arXiv preprint arXiv:2101.09868.'
---
[Download paper here](http://alexiland.github.io/files/CPT.pdf)
```
@misc{fu2021cpt,
      title={CPT: Efficient Deep Neural Network Training via Cyclic Precision}, 
      author={Yonggan Fu and Han Guo and Meng Li and Xin Yang and Yining Ding and Vikas Chandra and Yingyan Lin},
      year={2021},
      eprint={2101.09868},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```