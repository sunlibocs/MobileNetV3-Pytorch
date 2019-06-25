## Paper
- [Searching for MobileNetV3 paper](https://arxiv.org/abs/1905.02244)
- Author: Andrew Howard(Google Research), Mark Sandler(Google Research, Grace Chu(Google Research), Liang-Chieh Chen(Google Research), Bo Chen(Google Research), Mingxing Tan(Google Brain), Weijun Wang(Google Research), Yukun Zhu(Google Research), Ruoming Pang(Google Brain), Vijay Vasudevan(Google Brain), Quoc V. Le(Google Brain), Hartwig Adam(Google Research)

## Todo
- Experiments on ImageNet.

## Experiments
- For CIFAR-100 data, we experimented with resize (224, 224).<br>

| Datasets | Model | Accuracy | Epoch | Training Time | Parameters
| :---: | :---: | :---: | :---: | :---: | :---: |
CIFAR-100 | MobileNetV3(LARGE) | 68.9% | 62 | 5h(16G Mem + 1GPU) + 40min(32G Mem + 1GPU) | 3.99M
CIFAR-100 | MobileNetV3(SMALL) | 65.39% | 37 | 1h 50m(32G Mem + 1GPU) | 1.79M
IMAGENET | IN PROCESS | | | |

## Environment
- torch==1.1.0
