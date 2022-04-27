## Quantum Neural Network Error Mitigation: QCNN With Layerwise Learning
**Joe Vetere, Morgan Beadlescomb, Krishna Pothugunta**
*Ordered by Contribution*

### News

- **Apr 26, 2022**: Presented in ECE-884-SS22: Deep Learning @ Michigan State University

### Hypothesis
Quantum Convolutional Neural Networks built on Quantum Circuit Born Machines using Layerwise Learning techniques offer a superior approach to dealing with errors on NISQ devices than that of Quantum CNN, Hybrid CNN or Layerwise Learning approaches alone in quantum datasets.

### Abstract
Inspired by the works of Cong, Choi, & Lukin in [Quantum Convolutional Neural Networks](https://www.nature.com/articles/s41567-019-0648-8) and Andrea Skolik, Jarrod R. McClean, Masoud Mohseni, Patrick van der Smagt, Martin Leib with [Layerwise Learning for Quantum Neural Networks](https://arxiv.org/abs/2006.14904), we attempt to combine methodologies and apply strategy for classifying excitation data in a fashion that outperforms Hybrid QCNN models that have outperformed purely quantum solutions in the past. Leveraging defined intialization system states and layerwise learning upon a QCNN made up of layers of 1D convolution and pooling sequences, we examine a novel approach that does indeed outperform the quai-classical comptetition on this data set.


## Setup (for all baseline and experimental models)
All models have the following requirements:
- Python 3.7.13
- TensorFlow 2.7.0
- TensorFlow Quantum 0.6.1
- Cirq 0.13.1
- Sympy 1.8
- Numpy 1.16
- Matplotlib 3.0


## Model performance



## License

```
Placeholder
Copyright 2021-present NAVER Corp.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

## Citation

```
Placeholder
@inproceedings{heo2021pit,
    title={Rethinking Spatial Dimensions of Vision Transformers},
    author={Byeongho Heo and Sangdoo Yun and Dongyoon Han and Sanghyuk Chun and Junsuk Choe and Seong Joon Oh},
    booktitle = {International Conference on Computer Vision (ICCV)},
    year={2021},
}
```
