# ComputeShaderDemo
自己学习ComputeShader的一个简单Demo集合。  
相对应的文章链接为：
* [Unity中ComputeShader的基础介绍与使用](https://zhuanlan.zhihu.com/p/368307575)
* [Unity中使用ComputeShader做视锥剔除](https://zhuanlan.zhihu.com/p/376801370)
* [Unity中使用ComputeShader实现Hi-z遮挡剔除](https://zhuanlan.zhihu.com/p/396979267)
* [Unity中使用GeometryShader实现广告牌效果](https://zhuanlan.zhihu.com/p/585436751)

CommandBuffer分支，是解决了Hiz中，常规的Mono脚本生命周期中，无法获取“当前帧深度图”的问题（当前帧的深度图只能在OnPostRender获取，而Update函数在OnPostRender之前）。
