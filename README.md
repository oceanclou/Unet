# Unet
基于基本框架，更改神经网络模型为UNet  

6.22更新：微调网络模型的输入及其结构，修改精简整体代码，修改创建文件夹为UNet，将中间文件夹nn等去掉，将生成nn.txt文件修改为index.txt，同时在文件中增加mae和rmse  
补充：修改mse为rmse，训练过程中显示性能指标增加mae和rmse，修改生成图像名称为e0_0_o（output）和e0_0_t（target）格式，修改每次训练保存的模型名称为model_now.pth.tar  

6.23更新；解决了在已存在model_best.pth.tar时再运行程序报错的问题（RuntimeError: DataLoader worker (pid(s) 4388) exited unexpectedly以及后续将文件删除后出现的cuDNN error: CUDNN_STATUS_NOT_INITIALIZED），不过感觉可能是电脑的问题，因为是在重启电脑后发现可以运行了，估计是修改了一下代码，故上传更新
