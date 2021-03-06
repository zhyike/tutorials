# GPU 计算: CUDA 编程入门

GPU 加速计算是指同时利用图形处理器 (GPU) 和 CPU，加快科学、分析、工程、消费和企业应用程序的运行速度。GPU 加速器于 2007 年由 NVIDIA 率先推出，现已在世界各地为政府实验室、高校、公司以及中小型企业的高能效数据中心提供支持。GPU 能够使从汽车、手机和平板电脑到无人机和机器人等平台的应用程序加速运行.
GPU 加速计算可以提供非凡的应用程序性能，能将应用程序计算密集部分的工作负载转移到 GPU，同时仍由 CPU 运行其余程序代码。从用户的角度来看，应用程序的运行速度明显加快. 理解 GPU 和 CPU 之间区别的一种简单方式是比较它们如何处理任务。CPU 由专为顺序串行处理而优化的几个核心组成，而 GPU 则拥有一个由数以千计的更小、更高效的核心（专为同时处理多重任务而设计）组成的大规模并行计算架构。


CUDA是建立在NVIDIA的CPUs上的一个通用并行计算平台和编程模型，基于CUDA编程可以利用GPUs的并行计算引擎来更加高效地解决比较复杂的计算难题。近年来，GPU最成功的一个应用就是深度学习领域，基于GPU的并行计算已经成为训练深度学习模型的标配。


# Remark
The codes only work for Linux and Mac OSX, since a little system programming is required. However, user may
try to compile under Windows by changing
```
#define USE_UNIX 1
```
to 
```
#define USE_UNIX 0
```

Windows environment isn't tested. Thanks.
