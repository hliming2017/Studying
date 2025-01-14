# CTR预估系列：DeepCTR 一个基于深度学习的CTR模型包

在计算广告和推荐系统中，CTR 预估一直是一个核心问题。无论在工业界还是学术界都是一个热点研究问题，近年来也有若干相关的算法竞赛。本文介绍一个基于深度学习的 CTR 模型包 DeepCTR，具有简洁易用、模块化和可扩展的优点。（本文作者：沈伟臣）

## CTR预估简介

CTR预估是计算广告中最核心的算法之一，那么CTR预估是指什么呢？简单来说，CTR预估是对每次广告的点击情况做出预测，预测用户是点击还是不点击。

在计算广告和推荐系统中，CTR预估一直是一个核心问题。无论在工业界还是学术界都是一个热点研究问题，近年来也有若干相关的算法竞赛。
DeepCTR简介

人们通过构造有效的组合特征和使用复杂的模型来学习数据中的模式来提升效果。基于因子分解机的方法，可以通过向量内积的形式学习特征的交互，并且泛化到那些没有出现过的组合上。
随着深度神经网络在若干领域的巨大发展，近年来研究者也提出了若干基于深度学习的分解模型来同时学习低阶和高阶的特征交互，如：FNN,PNN,Wide&Deep,DeepFM,NFM,AFN,DIN等。

对于刚接触这方面的同学来说，可能对这些方法的细节还不太了解，虽然网上有很多介绍，但是代码却没有统一的形式，且使用起来不是很方便，从头开始实现成本又比较高。那么这里介绍一个基于深度学习的CTR模型包DeepCTR，无论是使用还是学习都很方便。

DeepCTR是一个简洁易用、模块化和可扩展的基于深度学习的CTR模型包。除了近年来主流模型外，还包括许多可用于轻松构建您自己的自定义模型的核心组件层。

您可以像使用其他Keras模型一样简单的通过 `model.fit()` 和 `model.predict()` 使用这些复杂模型。

文档主页：https://deepctr-doc.readthedocs.io/en/latest/index.html

代码主页：https://github.com/shenweichen/DeepCTR

- 本文作者：沈伟臣，浙江大学计算机硕士，wcshen1994@163.com
    - github主页：https://github.com/shenweichen