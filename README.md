# Data Poisoning Attacks and Evation Attacks



## 1. Evation Attacks (Adversarial Examples)

GitHub 上关于**对抗样本**的 repo


仓库 | 类型  |描述    
-----|-----|----    
[cleverhans](https://github.com/tensorflow/cleverhans)  | 攻击&防御  |`AML`领域鼻祖型的 repo，*Goodfellow* & *Papernot* 开发，提供攻击方法和防御方法。
[foolbox](https://github.com/bethgelab/foolbox/)  | 攻击  | 主要功能是用来产生对抗样本，实现了大概**15种**攻击方法，没有提供防御功能。
[machine_learning_adversarial_examples](https://github.com/rodgzilla/machine_learning_adversarial_examples  ) | 攻击 | 主要复现论文`Explaning and Harnessing Adversarial Examples`中的**FGSM算法**。 
[Adversarial_Learning_Paper](https://github.com/Guo-Yunzhe/Adversarial_Learning_Paper) |  awesome  | `AML`相关论文列表，包含`Survey`, `Attack`, `Defense`
[AdversarialDNN-Playground](https://github.com/QData/AdversarialDNN-Playground)  | 可视化  | 可视化攻击过程，同时在理论层面对攻击方法做了一定的分析（见仓库中的presentation）
[awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning)  | awesome | 总结了`AML`相关的`blogs`, `papers`, `talks`
[AdvBox](https://github.com/baidu/AdvBox)  | 攻击&防御  | 百度产品，提供各种攻击和防御方法，支持命令行直接生成对抗样本（zero-coding)
[adversarial-examples](https://github.com/ifding/adversarial-examples) | 攻击  | 理论层面，提供了几种常用攻击方法；现实层面，对**路标**进行攻击。
[adversarial_examples](https://github.com/duoergun0729/adversarial_examples)  | 攻击  | 提供了几种常用攻击方法，做了图表分析。
[Adversarial-Examples-Reading-List](https://github.com/chawins/Adversarial-Examples-Reading-List)  | awesome  | `AML`相关论文列表，包含`attacks`, `defenses`。作者是 UC Berkeley 博士生。
[nn_robust_attacks](https://github.com/carlini/nn_robust_attacks)  | 攻击  | 论文`Towards Evaluating the Robustness of Neural Networks`代码。作者从 UC Berkeley博士毕业。
[awesome-adversarial-examples-dl](https://github.com/chbrian/awesome-adversarial-examples-dl) | awesome | `AML`论文列表，包含`Attack`, `Defense`, `Application`
[FeatureSqueezing](https://github.com/uvasrg/FeatureSqueezing)   | 防御  | *Detecting Adversarial Examples in Deep Neural Network*。项目停止维护，移至[EvadeML-Zoo](http://evademl.org/zoo/)
[adversarial-example-pytorch](https://github.com/sarathknv/adversarial-examples-pytorch)   | 攻击  | pytorch 实现常用攻击方法，并且提供**可视化**功能。
[EvadeML-Zoo](https://github.com/mzweilin/EvadeML-Zoo)   | 攻击&防御  | 提供预训练模型，常用数据集，常用攻击方法；可视化对抗样本。

### 相关竞赛
* [NIPS 2017: Defense Against Adversarial Attack](https://www.kaggle.com/c/nips-2017-defense-against-adversarial-attack)
* [IJCAI-19阿里巴巴人工智能对抗算法竞赛](https://tianchi.aliyun.com/competition/entrance/231701/introduction?spm=5176.12281905.5490641.4.358b6bad39hWbP)

### 有用的链接
* https://evademl.org/
* https://secml.github.io/
* http://www.cleverhans.io/
* https://aaai18adversarial.github.io/ 
* https://www.openmined.org/ 
* https://www.pluribus-one.it/
* https://www.ieee-security.org/TC/SPW2018/DLS/
 


## 2. Poisoning Attacks

