# NeuroSkinning: Automatic Skin Binding for Production Characters with Deep Graph Networks

Siggraph 2019

by Lijuan Liu, Youyi Zheng, Di Tang, Yi Yuan, Changjie Fan, Kun Zhou

This paper presents a deep-learning-based method to automatically compute skin weights for skeleton-based deformation of production characters.

![Automatically predicting skin weights.](https://github.com/yiyuan1991/NeuroSkinning/blob/master/imgs/1.jpg)

Our method can be applied for different games.

![Example production characters.](https://github.com/yiyuan1991/NeuroSkinning/blob/master/imgs/2.jpg)

We first construct a graph for the input character mesh with its associate skeleton hierarchy. Each graph node encodes the mesh-skeleton attributes. The graph and node attributes are fed into our graph convolution net to predict the skin weight map.

![The pipeline of our method.](https://github.com/yiyuan1991/NeuroSkinning/blob/master/imgs/3.jpg)
