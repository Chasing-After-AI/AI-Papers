# AI-papers

人工智能相关论文

---

#### 1.小样本学习---WangNing

##### 1） Few-shot Object Detection via Feature Reweighting (ICCV2019) 

   这是ICCV2019的一片文章，主要是将Few-Shot Learning用于物体检测上面。其核心思是使用具有大量标签的base类训练一个特征调整模块，通过这个模块可以使用许多类的底层特征对需要检测图片的特征进行调整。这些底层特征能够在一定程度上反应所有类的通性，也可以理解为组成物体的属性（虽然我们检测的物体可能不属于同一类，但是在属性层面还是有很多相通的）然后，再将网络fine tune到小样本检测中去。

论文：https://arxiv.org/abs/1812.01866

代码：https://github.com/bingykang/Fewshot_Detection



#### 2.强化学习--- Xingbin Liao 
