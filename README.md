# DBMSolver: A Training-free Diffusion Bridge Sampler for High-Quality Image-to-Image Translation

[![arXiv](https://img.shields.io/badge/arXiv-Coming%20Soon-b31b1b.svg)](#)
[![CVPR 2026](https://img.shields.io/badge/CVPR-2026-blue.svg)](#)

> **[DBMSolver: A Training-free Diffusion Bridge Sampler for High-Quality Image-to-Image Translation](#)**  
> [Sankarshana Venugopal](mailto:sankarshana.v@gmail.com), [Mohammad Mostafavi](mailto:mostafavi.isfahani@gmail.com), [Jonghyun Choi](mailto:jonghyunchoi@snu.ac.kr)  
> Seoul National University  

---

### 🚧 Repository Under Construction 🚧
*We are finalizing the codebase and will release the full implementation of DBMSolver soon.*

---

## Abstract
Diffusion-based image-to-image (I2I) translation excels in high-fidelity generation but suffers from slow sampling in state-of-the-art Diffusion Bridge Models (DBMs), often requiring dozens of function evaluations (NFEs). We introduce **DBMSolver**, a training-free sampler that exploits the semi-linear structure of DBM's underlying SDE and ODE via exponential integrators, yielding highly-efficient 1st- and 2nd-order solutions. This reduces NFEs by up to 5x while boosting quality (e.g., FID drops 53% on DIODE at 20 NFEs vs. 2nd-order baseline). Experiments on inpainting, stylization, and semantics-to-image tasks across resolutions up to 256x256 show DBMSolver sets new SOTA efficiency-quality tradeoffs, enabling real-world applicability.

Citation
If you find our work useful for your research, please consider citing:

```
@inproceedings{venugopal2026dbmsolver,
  title={DBMSolver: A Training-free Diffusion Bridge Sampler for High-Quality Image-to-Image Translation},
  author={Venugopal, Sankarshana and Mostafavi, Mohammad and Choi, Jonghyun},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2026}
}
```
