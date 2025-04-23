電腦硬體設置:
	作業系統:Ubuntu 22.04.5 LTS
	顯示卡:GeForce RTX 4070 super
	CUDA版本:12.4
	cuDNN:8.6
訓練套件(pytorch)版本:

使用說明:訓練資料採用mini-ImageNet dataset，可至以下網站下載: https://cchsu.info/files/images.zip ，解壓縮後內部即有訓練資料切分的文字檔，將資料和文字檔與程式放在同資料夾中，即可執行

各個檔案說明:
dynamic_resnet18.ipynb:修改後的ResNet18模型
raw_resnet18.ipynb:原生ResNet18模型

參考資料:
paper:Chen, Yinpeng, et al. "Dynamic convolution: Attention over convolution kernels." Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2020.
部分程式碼參考[kaijieshi7](https://github.com/kaijieshi7/Dynamic-convolution-Pytorch) 
