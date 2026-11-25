# TSCA-ResNet50 Dataset

This dataset contains 4,016 RGB images of sawn timber surfaces in five defect categories. We screened the source images, created the training, validation, and test splits, and applied data augmentation to the training set. The dataset comprises 2,543 selected original images and 1,473 augmented training images.

| Defect class | Train | Validation | Test |
| --- | ---: | ---: | ---: |
| Crack | 420 | 75 | 78 |
| Dead knot | 766 | 105 | 101 |
| Live knot | 1,050 | 122 | 125 |
| Resin pocket | 656 | 66 | 62 |
| Missing knot | 320 | 34 | 36 |
| Total | 3,212 | 402 | 402 |

## Download

Download the three ZIP archives from the [v1.0.0 release](https://github.com/sujianshuai/TSCA-ResNet50-Dataset/releases/tag/v1.0.0) and extract them into the same directory. The training images are spread across two archives. The third archive contains the validation and test images and the original annotations. The class subdirectories under train, val, and test identify the image-level categories. The labels directory contains the original source annotations.

## License and Attribution

The original images and annotations were published by Pavel Kodytek, Alexandra Bodzas, and Petr Bilik under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). The [source dataset](https://doi.org/10.5281/zenodo.4694695) is available on Zenodo.

The screening, split organization, and augmentation in this release are provided under [CC BY 4.0](LICENSE). Please cite the original dataset and this release when reusing the data.