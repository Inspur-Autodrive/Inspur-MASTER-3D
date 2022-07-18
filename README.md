# Inspur-MASTER-3D
Inspur Autodrive Team, MASTER (Multi-camerA Spatial and Temporal feature ExtractoR) 

## Results
### 3D Object Detection (on nuScenes test)

|   Model   | mAP  | NDS  |
| :-------: | :--: | :--: |
| Inspur-MASTER-1600 |46.85 | 57.47 |

### 3D Object Detection (on nuScenes val)

|   Model   | mAP  | NDS  |
| :-------: | :--: | :--: |
| Inspur-MASTER-704| 35.91 | 49.75 |


## Get Started

### Environment
This implementation is build upon [mmdetection3d](https://github.com/open-mmlab/mmdetection3d), please follow the steps in [install.md](./docs/install.md) to prepare the environment.

### Data
Please follow the official instructions of mmdetection3d to process the nuScenes dataset.(https://mmdetection3d.readthedocs.io/en/latest/datasets/nuscenes_det.html)


## Acknowledgement
Many thanks to the following open-source projects:
* [mmdetection3d](https://github.com/open-mmlab/mmdetection3d)

## Reference

```bibtex
@{author={Gongzhan, Zhaoyun, Lijun, Zhuhong}}
```
