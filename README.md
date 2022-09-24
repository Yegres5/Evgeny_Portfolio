# [Project 1: Neural Network based algorithm to solve missile navigation problem](https://github.com/Yegres5/missile-solution)
### R&D Reinforcement learning project
* Created a tool based on Q-learning algorithm, that trains neural network to solve air-to-air missile navigation problem.
* Sucsessfully presented and proved efficiancy of neural networks in this type of tasks
* Used advanced teqniques such as Dueling Q-learning [Arxiv](https://arxiv.org/abs/1511.06581) and Double Q-learning [Neurips](https://proceedings.neurips.cc/paper/2010/file/091d584fced301b442654dd8c23b3fc9-Paper.pdf)
* Used Pytorch as Neural Network framework, AWS EC2 for cloud computation, Tensorboard to monitor neural network train progression
* Used OpenAI Gym framework to build [custom simulation environment](https://github.com/Yegres5/missile-env)
* Used YAPPI profiler to optimize computations of custom environment

Graph below represent hit probability: for blue - trained neural network, and 3 different methods for different reactions of environment.
<img src="https://github.com/Yegres5/Evgeny_Portfolio/blob/d9953b112e3afcca187b0be296803d9ff3025aaa/images/Average%20score.jpg?raw=true" width="726"/>

# [Project 2: Simpsons image classification](https://colab.research.google.com/drive/1uK5jME11mfnxepZ2WO8lLMNl9yO5pjvx?usp=sharing)
### Simpsons image classification project based on [kaggle competition](https://www.kaggle.com/competitions/journey-springfield). Final score 0.99256 (F1 metric)

<img src="https://github.com/Yegres5/Evgeny_Portfolio/blob/main/images/Simpsons.png?raw=true" width="726"/>

* Experimented with different neural network arcitectures: EfficientNet (b3 with final score 0.99256), VGG (VGG16 with final score 0.97768)
* Used NVIDIA Dali to augment the data which allowed to use GPU for preprocessing

# [Project 3: Skin lesions semantic segmentation](https://colab.research.google.com/drive/1J_gzinKCsiNcgcz-zsaQQ06Y4GiUuQyF?usp=sharing)
### [Dataset](https://www.fc.up.pt/addi/ph2%20database.html) consist of photographs of two types of skin lesions: melanoma and moles. Task was to segment them on the image.
<img src="https://github.com/Yegres5/Evgeny_Portfolio/blob/main/images/SkinSegmentation.png?raw=true" width="726"/>

* Compared different neural network architectures such as SegNet and U-Net (tried different approached MaxPooling and transpose-convolution layers) 
* Metric: IOU
* Experimented with different [loss functions](https://arxiv.org/pdf/2006.14822.pdf): [BCE](https://www.tensorflow.org/api_docs/python/tf/nn/sigmoid_cross_entropy_with_logits), DICE, Focal loss, Log-Cosh Dice Loss, TverskyLoss, Focal Tversky Loss
* Small report (on russian) at the end of colab notebook:
<img src="https://github.com/Yegres5/Evgeny_Portfolio/blob/main/images/ReportSkin.png?raw=true"/>

# [Project 4: creepy GAN project]
### Point of the project was to try to implement GAN architecture from scratch. [Dataset](https://drive.google.com/file/d/1KWPc4Pa7u2TWekUvNu9rTSO0U2eOlZA9/view?usp=sharing) used in project was based on [FFHQ](https://github.com/NVlabs/ffhq-dataset) (high quality image dataset of human faces)

<img src="https://github.com/Yegres5/Evgeny_Portfolio/blob/main/images/FacesOriginal.png?raw=true" width="726"/>

* Successfully implemented GAN from scratch

<img src="https://github.com/Yegres5/Evgeny_Portfolio/blob/main/images/CreepyFaces.png?raw=true" width="726"/>

* Tested quality of generated images with Leave-one-out classifier (0.531)
* Used PCA on discriminator results to visualaze the data results

<img src="https://github.com/Yegres5/Evgeny_Portfolio/blob/main/images/GAN_PCA.png?raw=true" width="726"/>
