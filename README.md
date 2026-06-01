<div align="left">

# TIENet: A Tri-Interaction Enhancement Network for Multi-Modal Person Re-Identification (TNNLS 2025)

</div>

<p align="left">
Official PyTorch Implementation of TIENet: A Tri-Interaction Enhancement Network for Multi-Modal Person Re-Identification
</p>

<p align="left">
  <a href="https://ieeexplore.ieee.org/abstract/document/10934016">📄 Paper</a>
</p>

---

# Abstract

Multi-modal person re-identification (ReID), which aims to learn modality-complementary information by utilizing multi-modal images simultaneously for person retrieval, is crucial for achieving all-time and all-weather monitoring. Existing methods try to address this issue through modality fusion to absorb complementary information. However, most of these methods are limited to the spatial domain only and usually overlook the intra-/inter-modal interactions during feature fusion, resulting in insufficient learning of modality-specific and complementary information. To address these issues, we propose a Tri-Interaction Enhancement Network (TIENet), which contains three modules: Spatial-Frequency Interaction (SFI), Inter-Modal Mask Interaction (IMMI) and Intra-Modal Feature Fusion (IMFF). Specifically, the SFI boosts the modality-specific representation by integrating the amplitude-guided attention mechanism into the phase space, combined with spatial domain convolution to achieve fine-grained information learning. Meanwhile, the IMMI enhances the richness of the feature descriptors by embedding the inter-modal relationships to preserve complementary information. Finally, the IMFF module considers the structure of the human body and integrates intra-modal contextual information.Extensive experimental results demonstrate the effectiveness of our method, achieving superior performances on RGBNT201 and MARKET1501_RGBNT datasets. 

---


# Framework Overview

<p align="center">
  <img src="https://github.com/DWJ11/TIENet-A-Tri-Interaction-Enhancement-Network-for-Multimodal-Person-Reidentification/blob/main/figures/main.png" width="95%">
</p>

---



# Experimental Results

## Results

<p align="center">
  <img src="https://github.com/DWJ11/TIENet-A-Tri-Interaction-Enhancement-Network-for-Multimodal-Person-Reidentification/blob/main/figures/Snipaste_2026-06-01_10-33-49.png" width="90%">
</p>

### Models
<a href="https://pan.quark.cn/s/1d3460aee05d">Download</a> |




---

# Visualization Results

## Distribution of distances for positive/negative sample pairs

<p align="center">
  <img src="https://github.com/DWJ11/TIENet-A-Tri-Interaction-Enhancement-Network-for-Multimodal-Person-Reidentification/blob/main/figures/distance.png" width="95%">
</p>

---

## T-SNE results

<p align="center">
  <img src="https://github.com/DWJ11/TIENet-A-Tri-Interaction-Enhancement-Network-for-Multimodal-Person-Reidentification/blob/main/figures/tsne.png" width="95%">
</p>

---

# Citation

If you find this project useful for your research, please consider citing:

```bibtex
@article{yang2025tienet,
  title={Tienet: A tri-interaction enhancement network for multimodal person reidentification},
  author={Yang, Xi and Dong, Wenjiao and Cheng, De and Wang, Nannan and Gao, Xinbo},
  journal={IEEE Transactions on Neural Networks and Learning Systems},
  year={2025},
  publisher={IEEE}
}

```

---

<div align="center">

</div>

</div>
