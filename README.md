# modnet_portrait_matting
人像抠图
# log
1.    
2.多尺度训练  
3.数据合成：模拟合成横屏、竖屏样本（pc端16:9、手机端9:16），随机尺度缩小人物进行贴图。 
4.类似于mosic拼图来做增强  
5.作者提示计算背景与前景的颜色差距，使合成数据更加真实   
6.  
7.tps薄板样条插值来模拟摄像头运动产生的图像形变  
8.随机裁剪，仿射变换，高斯噪声，随机左右翻转，亮度、对比度、色调调整  
9.  
10. 分割分支精度对最终的效果影响很大，分割分支损失调整到decoder到原图尺寸再计算  
11. 使用类unet结构重构网络，类似rvm训练策略在训练matte时穿插训练segmentation分支，提升明显

# ref
https://github.com/ZHKKKe/MODNet  
https://github.com/thuyngch/Human-Segmentation-PyTorch
