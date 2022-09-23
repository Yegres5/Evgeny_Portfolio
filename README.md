# Evgeny
ML portfolio
# [Project 1: Neural Network based algorithm to solve missile navigation problem. R&D Reinforcement learning project.](https://github.com/Yegres5/missile-solution)
* Created a tool based on Q-learning algorithm, that trains neural network to solve air-to-air missile navigation problem.
* Sucsessfully presented and proved efficiancy of neural networks in this type of tasks
* Used advanced teqniques such as Dueling Q-learning [Arxiv](https://arxiv.org/abs/1511.06581) and Double Q-learning [Neurips](https://proceedings.neurips.cc/paper/2010/file/091d584fced301b442654dd8c23b3fc9-Paper.pdf)
* Used Pytorch as Neural Network framework, AWS EC2 for cloud computation, Tensorboard to monitor neural network train progression
* Used OpenAI Gym framework to build [custom simulation environment](https://github.com/Yegres5/missile-env)
* Used YAPPI profiler to optimize computations of custom environment

Average reward for blue - trained neural network, and 3 different methods for different reactions of environment:
<img src="https://github.com/Yegres5/Evgeny_Portfolio/blob/c2890b6ef763092c42b1f1a91ca8c16f56588419/images/loss_log.png" width="726">
<img src="https://camo.githubusercontent.com/331400aee821efda2e36ee9b3bc8bce93b975109/68747470733a2f2f6779617a6f2e636f6d2f65623563353734316236613961313663363932313730613431613439633835382e706e67" width="200" height="400" />
