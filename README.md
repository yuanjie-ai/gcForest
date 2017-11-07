<h1 align = "center">:rocket: 深度森林 :facepunch:</h1>

---
## [1. 原理][1]

![算法结构][3]

---
## [2. 实战][2.1]
- [参数解析][2.2]
```
gcf = gcForest(shape_1X=None,  # 单个样本元素的形状shape(图像形状), 调用mg_scanning时需要！对于序列数据，可以给出单个int
               n_mgsRFtree=30,
               window=None,  # 滑动窗口的大小, 类比CNN
               stride=1,  # 滑动步长
               cascade_test_size=0.2,
               n_cascadeRF=2,
               n_cascadeRFtree=101,
               cascade_layer=np.inf,
               min_samples_mgs=0.1,
               min_samples_cascade=0.05,
               tolerance=0.0,  # 提升的精度小于tolerance时，就停止迭代
               n_jobs=1)
```
- [算法预测股指期货涨跌][2.3]
---
[1]: http://blog.csdn.net/xbinworld/article/details/60466552
[1.1]: https://www.qcloud.com/community/article/536731001491381531?!preview

[2.1]: http://nbviewer.jupyter.org/github/Jie-Yuan/gcForest/blob/master/gcForest_tuto.ipynb
[2.2]: https://www.qcloud.com/community/article/606289
[2.3]: https://mp.weixin.qq.com/s?__biz=MzAxNTc0Mjg0Mg==&mid=2653285179&idx=1&sn=f3d07a411aff07a7c49125ce1a057db4

[3]: https://github.com/Jie-Yuan/gcForest/blob/master/mgs.png
