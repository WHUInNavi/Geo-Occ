# Geo-Occ
Geo-Occ: A pioneering framework and multi-source dataset for Cross-View 3D Occupancy Prediction, integrating satellite imagery and vector maps via Visibility-Aware Dynamic Fusion.

## 🏆 Main Results

We provide the pre-trained weights for Geo-Occ under different configurations. All models are trained on the Geo-Occ-Dataset.

| Config | Frame | Backbone | Backbone(Sat/Map) | Input Size | mIoU | Model |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **M1: FlashOcc** | 1 | R50 | - | 256x704 | 32.01 | [🔗 gdrive](https://drive.google.com/file/d/1k9BzXB2nRyvXhqf7GQx3XNSej6Oq6I-B/view) |
| **V1: SA-Occ** | 1 | R50 | R18 | 256x704 | 37.84 | [🔗 gdrive](https://drive.google.com/file/d/1Dh2B_Z1OYYBrepsUvw1c1wbbLv_3iCcH/view) |
| **V1: Geo-Occ** | 1 | R50 | R18 | 256x704 | **39.58** | [🔗 gdrive](https://drive.google.com/file/d/16z47nqU0imfzJsbEF7yGh4zTiazs5Hvj/view?usp=sharing) |
| **M3: FlashOcc-4D-Stereo** | 2 | Swin-B | - | 512x1408 | 43.52 | [🔗 gdrive](https://drive.google.com/file/d/1f6E6Bm6enIJETSEbfXs57M0iOUU997kU/view) |
| **V5: SA-Occ** | 2 | Swin-B | R50 | 512x1408 | 43.06 | [🔗 gdrive](https://drive.google.com/file/d/1wnOGNadRJk9pBpM8Z0YJiad5jYlNdeOU/view) |
| **V2: Geo-Occ*** | 2 | Swin-B | R50 | 512x1408 | **44.62** | [🔗 gdrive](https://drive.google.com/file/d/12Xsjv0ot9QWEGx_UqF0m1mMp8aR6x6pb/view?usp=sharing) |

## 💾 Dataset Access

The Geo-Occ dataset is available for academic use. You can download the full version from Google Drive via the link below:

[![Google Drive](https://img.shields.io/badge/Google%20Drive-Geo--Occ%20Dataset-blue?logo=googledrive&logoColor=white&style=for-the-badge)](https://drive.google.com/file/d/15r-wwa26OD7Yn7XGhbFAqK8CaInLb4aY/view?usp=sharing)
