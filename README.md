# Model Compression
This project focuses on the model pruning and quantization. We first introduced the working principles of the algorithms. In the experiments, we selected CIFAR-10 as the dataset and VGG as the baseline and compared the two algorithms. Furthermore, we qualitatively and quantitatively analyzed the performance of them, and gave their respective applicable scenarios. The results show that pruning compressed the model size by 50.01% and the accuracy dropped by 0.25%, while quantization compressed the model size by 74.99% with the accuracy dropped by 1.10%. That means, in this case, quantization performed better than pruning. At last, we discussed the limitations and the development directions.

# Running detail
The code is in the ".code/" directory
## For ".code/quantization"
If you want to run the quantization code, you have two option:

1. Refer to the kaggle link:
	VGG stat and dy Quantization
	https://www.kaggle.com/code/shadowcattin/vgg-stat-and-dy-quantization
	
	Resnet18 dynamic and stat quantization
	https://www.kaggle.com/code/shadowcattin/resnet18-dynamic-and-stat-quantization

2. Offline jupyter notebook file:
	For the Resnet18 dynamic and stat quantization, you can run directly
	For the VGG stat and dy Quantization, you need to move the file "vgg16_2.pth" to the same path of jupyter notebook.
(Or you can download it in: https://www.kaggle.com/datasets/shadowcattin/ci-vgg-pretrain)

## For ".code/purning"
If you want to run the purning code, you can run the jupyter file:
1. For ResNet18, run 'unstructured_pruning_ResNet18.ipynb' file.
2. For VGG16, run 'unstructured_pruning_VGG16.ipynb' file.

Note: If you do not want to pretrain model again, you can download it from kaggle and put them to the same path of codes.
a. ResNet18: https://www.kaggle.com/datasets/shadowcattin/resnet18-pretrained
b. VGG16: https://www.kaggle.com/datasets/shadowcattin/ci-vgg-pretrain/data
