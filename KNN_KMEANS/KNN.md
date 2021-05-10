原始懒惰的机器学习方法，[K最近邻算法](https://www.bilibili.com/video/BV13K411H7Zs)    

```
step1:    
define space and distance function    
定义空间，距离公式   
step2:    
input known/unknown samples   
录入样本点信息    
step3:   
find Top-K nearest samples
找最近的K个样本   
step4:   
find the majorities in the k nearest neighbor    
找到最近的K个样本中，那个类别最多    
```

### pros
简单直观
### cons
K值敏感，不同的K得到不同的结果   
只观测样本的局部分布，忽略全局   
