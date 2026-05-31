1. Train
   ```python
    CUDA_VISIBLE_DEVICES=0 python ./scripts/mainMultiModal.py --config-file ./configs/RGBNT_ieee_part_margin.yaml --seed 40 test.evaluate False
    CUDA_VISIBLE_DEVICES=0 python ./scripts/mainMultiModal.py --config-file ./configs/im_r50_softmax_256x128_amsgrad_MARKET_ieee.yaml --seed 40 test.evaluate False
   ```

2. Test
   ```python
    CUDA_VISIBLE_DEVICES=0 python ./scripts/mainMultiModal.py --config-file ./configs/RGBNT_ieee_part_margin.yaml --seed 40 test.evaluate True model.load_weights bestpath
    CUDA_VISIBLE_DEVICES=0 python ./scripts/mainMultiModal.py --config-file ./configs/im_r50_softmax_256x128_amsgrad_MARKET_ieee.yaml --seed 40 test.evaluate True model.load_weights bestpath   
```

3. Bestpath
   Qurk Drive Link: https://pan.quark.cn/s/1d3460aee05d


4.Reference：
@article{yang2025tienet,
  title={Tienet: A tri-interaction enhancement network for multimodal person reidentification},
  author={Yang, Xi and Dong, Wenjiao and Cheng, De and Wang, Nannan and Gao, Xinbo},
  journal={IEEE Transactions on Neural Networks and Learning Systems},
  year={2025},
  publisher={IEEE}
}

