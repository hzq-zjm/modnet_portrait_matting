# modnet_portrait_matting
人像抠图
# TODO & rethink 
1.损失比重优化,对于自身合成数据 5:5:1效果不错
2.多尺度训练
3.数据合成中人像随机缩放再贴图,也可增加标准该种场景样本（人像面积占比较低） 
4.类似于masic数据增强  
5.作者提示计算背景与前景的颜色差距，使合成数据更加真实  
6.soc自监督策略效果提升明显
7....

# ref
https://github.com/ZHKKKe/MODNet  
https://github.com/thuyngch/Human-Segmentation-PyTorch
