# dl_project1
This is the mini project 1 for NYU ECE 7123 Deep Learning.

Deep learning network ResNet-18 has a good effect on image classification. How-
ever, it has some problems that has a relatively large number of parameters. In this
tasks, we design a new model based on Resnet-18. We have adjusted some parameters-
in network and added Adam optimizer, batch norm regularization,and some
data augment strategies to optimize the network. Eventually, we get a good network-,
size of parameters in which is less than 5m, and the max accuracy can be
up to 93.75% on training CIFAR-10.

Put the AutoAugment.py and ops.py into any folder, and change the code in second block-
“C:\Users\suxin\PycharmProjects\pythonProject” to the folder path which you save that two-
.py file before. Then click run button (for jupyter notebook) to run all cell.
