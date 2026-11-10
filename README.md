# ViT-OutdoorLoc

ViT-OutdoorLoc is a multi-scale and multi-modal Vision Transformer framework for UAV localization in outdoor environments under GPS/GNSS-denied or unreliable conditions.

The proposed approach combines three complementary data sources:

- **RGB Images:** Local visual information.
- **Satellite Images:** Global spatial context.
- **DEM:** Terrain elevation information.

Three architectures are investigated: ViT Baseline, Multi-Scale ViT, and Multi-Scale Multimodal ViT.

### Dataset
Experiments are conducted using the **UAVLoc-M3 dataset**, covering three outdoor regions:
- AnYangRiver
- Chongmingdao
- CuiJiaQiao

### Execution Environment
The code is designed to run on **Kaggle Notebooks**. To execute the experiments, add the UAVLoc-M3 dataset as a Kaggle Notebook input and enable GPU acceleration when available.

### Objective
Improve UAV 6-DoF pose estimation through multi-scale visual representations and multimodal information fusion.

**Status:** Research and experimental development.
