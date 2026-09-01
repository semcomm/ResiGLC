# ResiGLC: Loss-Resilient Semantic Communication over Packet-Loss Networks at Extreme-Low Bandwidth

This repository contains the code for ResiGLC, a loss-resilient image semantic communication framework. 

<p align="center">
  <a href="https://ieeexplore.ieee.org/abstract/document/11663281">
    <img src="https://img.shields.io/badge/IEEE-blue.svg">
  </a>
  <a href="https://arxiv.org/abs/2608.19590">
    <img src="https://img.shields.io/badge/arXiv-2608.19590-b31b1b.svg" alt="arXiv:2608.04891">
  </a>
</p>

## 📝 Abstract

In extreme-low bandwidth network scenarios, generative semantic codecs have emerged as promising solutions to reduce bandwidth cost for visual communications. However, these learned codecs are usually optimized solely for compression efficiency and thus not robust against transmission errors. Corruptions due to packet-loss among these highly compact generative latent representations often cause more critical degradation in fidelity and realism, intensified by the severe error propagation across the latent contexts and multi-step decoding process. In this paper, we propose "ResiGLC", a novel loss-resilient generative latent coding framework designed for robust semantic communication over extreme-low bandwidth packet-loss networks. Motivated by the inherent goal-consistency between generation and compression, we sufficiently exploit the impressive in-context predictive capabilities of language models. Integrated with the masked learning strategy, our model supports arbitrary context modeling of latent codes, which could mitigate the error propagation and handle unpredictable packet loss patterns. At the receiver, a progressive resilient decoding pipeline is presented, which leverages both the contextual relationship of the latent codes and the multi-modal semantic prior in the generative latent space, separately. By jointly optimizing toward both compression efficiency and packet-loss resilience, our proposed progressive decoding mechanism offers graceful performance when dealing with dynamic packet losses. Through extensive experimental evaluations, we establish that under packet-loss network conditions, ResiGLC can effectively improve the loss-resilience in terms of perceptual fidelity and realism qualities with extreme-low bandwidth cost. 

## 📦 Code release

[2026-09] The code will be released in a few weeks. Stay tuned.

## 📚 Citation

If you find this paper helpful in your research or work, please cite:

```bibtex
@article{yao2026loss,
  title={Loss-Resilient Semantic Communication over Packet-Loss Networks at Extreme-Low Bandwidth},
  author={Shengshi, Yao and Jincheng, Dai and Sixian, Wang and Guo, Lu and Kai, Niu and Wenjun, Xu and Wenjun, Zhang and Ping, Zhang},
  journal={IEEE Transactions on Mobile Computing},
  volume={},
  number={},
  pages={1--14},
  year={2026},
  publisher={IEEE},
  doi={10.1109/TMC.2026.3726512}
}
```
