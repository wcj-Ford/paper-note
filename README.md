# paper-note
论文归类

The Scale Problem：

个人认识有限，现在应用深度学习的计算机视觉的两个基础问题是： Scale and Classification

Classification已经解决的很好了（除了部分病态情况，遮挡、化妆、极低的分辨率）

Scale问题我认为是目前计算机视觉研究的痛点，CNN具有优秀的分类性能，但有个前提是要在同一尺度下的图像，目前很多方法使用缩放、使用中间层特征，存在非常多的冗余运算。尺度与密度与3D的Depth是有关联的，可以从几何的角度入手。

图像分割是对每一个像素点的分类，我认为可以看作是对不同图像区域的分类，取图像的一个子区域对其分类，结果看作该区域中心点像素的类别。图像分割里面很重要的一个方面是合理的利用Context信息，这个Context与Scale

PCC Net: Perspective Crowd Counting via Spatial Convolutional Network

https://arxiv.org/pdf/1905.10085.pdf

从透视投影的角度去看待 Crowd Counting问题，提出使用上、下、左、右四种图像上的空间划分方法來空间尺度变化。



