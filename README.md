# modnet_portrait_matting
人像抠图
# TODO & rethink 
1.损失比重优化,对于自身合成数据 5:5:1效果不错 ✌️  
2.多尺度训练   ✌️  
3.数据合成中人像随机缩放再贴图,增加标注横、屏竖屏等各个场景样本（人像面积占比较低） ✌️  
4.类似于mosic拼图来做增强   ✌️  
5.作者提示计算背景与前景的颜色差距，使合成数据更加真实   ✍️  
6.soc自监督策略效果提升明显  ✌️  
7.tps薄板样条插值来模拟摄像头运动产生的图像形变  ✍️  
8.随机裁剪，仿射变换，高斯噪声，随机左右翻转，亮度、对比度、色调调整  ✌️  
9.pc端上线，手机端压缩  ✍️   
10. 分割分支精度对最终的效果影响很大，对于压缩后的模型重新训练分割分支。 ✌️ 

# ref
https://github.com/ZHKKKe/MODNet  
https://github.com/thuyngch/Human-Segmentation-PyTorch
