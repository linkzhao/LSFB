# LSFB: A Low-cost and Scalable Framework to Build Large-Scale Localization Benchmark for Augmented Reality
Nowadays the application of AR is expanding from small or medium environments to large-scale environments, where the visual-based localization in the large-scale environments becomes a critical demand. Current visual-based localization techniques face robustness challenges in complex large-scale environments, requiring tremendous number of data with groundtruth localization for algorithm benchmarking or model training. The previous groundtruth solutions can only be used outdoors, or require high equipment/labor costs, so they cannot be scalable to large environments for both indoors and outdoors, nor can they produce large amounts of data at a feasible cost. In this work, we propose LSFB, a novel low-cost and scalable framework to build localization benchmark in large-scale indoor and outdoor environments. The key is to reconstruct an accurate HD map of the environment. For each visual-inertial sequence captured in the environment, the groundtruth poses are obtained by joint optimization taking both the HD map and visual-inertial constraints. The experiments demonstrate the obtained groundtruth poses have cm-level accuracy. We use the proposed method to collect a localization dataset by mobile phones and AR glasses in various environments with various motions, and release the dataset as the first large-scale localization benchmark for AR.





# Citation

If you find this code useful for your research, please use the following BibTeX entry.

```bibtex
@ARTICLE{10223237,
  author={Liu, Haomin and Zhao, Linsheng and Peng, Zhen and Xie, Weijian and Jiang, Mingxuan and Zha, Hongbin and Bao, Hujun and Zhang, Guofeng},
  journal={IEEE Transactions on Circuits and Systems for Video Technology}, 
  title={A Low-cost and Scalable Framework to Build Large-Scale Localization Benchmark for Augmented Reality}, 
  year={2023},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TCSVT.2023.3306160}}
```
