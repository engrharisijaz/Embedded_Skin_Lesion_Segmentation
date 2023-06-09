# Embedded_Skin_Lesion_Segmentation

## Abstract:
Skin cancer is a global health concern that might be alleviated by embedded device-assisted diagnosis due to the limited number of dermatologists in many regions. An embedded device integrated with a camera for skin cancer diagnosis is of great interest worldwide, potentially enhancing mobile dermo-scopic diagnosis for the most malignant skin cancer, melanoma. The automatic segmentation of skin lesions from images is a crucial step towards reaching this objective. Deep learning-based models provide state-of-the-art accuracy in dermoscopic image analysis and diagnosis. Deep learning, on the other hand, has high computation costs, making it difficult to integrate such models on an embedded platform with limited resources. For this purpose, we proposed lightweight encoder-decoder deep learning architectures, referred to as MobileUNet and EfficientUNet, with the encoder based on the MobileNetV2 bottleneck block and the EfficientNetB0 MBConv block, respectively, and the decoder being identical to the baseline UNet model. The proposed architectures are evaluated on two publicly available datasets, ISIC 2017 and ISIC 2018. Models run efficiently on embedded platforms, achieving up to 12 percent higher performance compared to the baseline model with minimal power and memory requirements without compromising accuracy or the Jaccard index compared to the baseline model.
## Model
![10136688-fig-3-source-small](https://github.com/engrharisijaz/Embedded_Skin_Lesion_Segmentation/assets/92294452/2c149745-1773-458d-9dc5-68995689ba0c)

## Comparison of skin lesion, ground truth and binary mask generated by models
![10136688-fig-5-source-small](https://github.com/engrharisijaz/Embedded_Skin_Lesion_Segmentation/assets/92294452/4681494a-40de-4a71-b689-ebee1486d0f2)

## Cite:
H. Ijaz, H. Sultan, M. Altaf and A. Waris, "Embedded Skin Lesion Segmentation using Lightweight Encoder-Decoder Architectures," 2023 3rd International Conference on Artificial Intelligence (ICAI), Islamabad, Pakistan, 2023, pp. 176-181, doi: 10.1109/ICAI58407.2023.10136688.


@INPROCEEDINGS{10136688,
  author={Ijaz, Haris and Sultan, Hajrah and Altaf, Mishal and Waris, Asim},
  booktitle={2023 3rd International Conference on Artificial Intelligence (ICAI)}, 
  title={Embedded Skin Lesion Segmentation using Lightweight Encoder-Decoder Architectures}, 
  year={2023},
  volume={},
  number={},
  pages={176-181},
  doi={10.1109/ICAI58407.2023.10136688}}


