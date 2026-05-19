# SelectVision: Adaptive Vision Resolution Selection for Visual Document Understanding

**ICDAR 2025**

## Abstract

SelectVision is a novel adaptive resolution selection framework for Visual Document Understanding. It introduces two core components: the **Resolution-Slicing Selector (RsSelector)**, which captures document information density and performs adaptive patch slicing through resolution selection, and a **multi-stage training strategy with Mixed Preference Optimization (MPO)**. The RsSelector assigns high-resolution representations to regions with dense information and small font sizes while applying lower-resolution representations to areas with redundant information. This method captures fine-grained visual representations while maintaining modeling efficiency.

## Results

SelectVision achieves state-of-the-art performance on document understanding benchmarks:

- **ChartQA**: 84.3%
- **WikiTableQuestions (WTQ)**: 59.2%
- **TabFact**: 83.9%

## Installation

Coming soon.

## Usage

Coming soon.

## Citation

If you find this work useful, please cite:

```bibtex
@inproceedings{he2025selectvision,
  title={SelectVision: Adaptive Vision Resolution Selection for Visual Document Understanding},
  author={He, Zhongjiang and Yuan, Ye and Zhao, An and Fang, Han and Sun, Hao and Liang, Kongming and Ma, Zhanyu},
  booktitle={International Conference on Document Analysis and Recognition (ICDAR)},
  year={2025}
}
```
