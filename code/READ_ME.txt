For "./quantization"
If you want to run the quantization code, you have two option:

1. refer to the kaggle link:
	VGG stat and dy Quantization
	https://www.kaggle.com/code/shadowcattin/vgg-stat-and-dy-quantization
	
	
	Resnet18 dynamic and stat quantization
	https://www.kaggle.com/code/shadowcattin/resnet18-dynamic-and-stat-quantization

2. offline jupyter notebook file:
	For the Resnet18 dynamic and stat quantization, you can run directly
	For the VGG stat and dy Quantization, you need to move the file "vgg16_2.pth" to the same path of jupyter notebook.
(Or you can download it in: https://www.kaggle.com/datasets/shadowcattin/ci-vgg-pretrain)


-----------------------------------------------------------------------------------------
For "./purning"
If you want to run the purning code
	jupyter file:
		For ResNet18, run 'unstructured_pruning_ResNet18.ipynb' file.
		For VGG16, run 'unstructured_pruning_VGG16.ipynb' file.
		If you do not want to pretrain model again, you can download it from
	ResNet18: https://www.kaggle.com/datasets/shadowcattin/resnet18-pretrained
	VGG16: https://www.kaggle.com/datasets/shadowcattin/ci-vgg-pretrain/data
	Download them to the same path of codes.