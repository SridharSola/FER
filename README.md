# FER
This project uses deep learning to perfrom facial expression recognition. We used ResNet18 pretrained on MSCeleb-1M as our
network. Our experiments used two benchmark datasets: RAFDB and FERPlus.\ 
Further, a face mask was synthetically placed on images of these datasets so we could run experiments on masked images. \
The results of these experiments served as baseline results for further studies (see projects on Knowledge Distillation and 
Contrastive Learning). 

# Datasets

![RAFDB](https://user-images.githubusercontent.com/64302305/172004582-54011bb9-b6f9-4bd3-a8cb-50ab98079a4d.jpg)\

![FERPlus](https://user-images.githubusercontent.com/64302305/172004587-f89c0de5-0b63-4437-a867-abba32d7eb85.jpg)

# Experiments

Experiment 1 – Training ResNet18 on non-masked images.\
Experiment 2 – Training ResNet18 on masked images.\
Experiment 3 – Training ResNet18 on masked images when pre-trained on non-masked images.\
Experiment 4 – Training ResNet18 on Mixed (masked and non-masked) dataset.\

# Results

![Results](https://user-images.githubusercontent.com/64302305/172006032-c532c2a3-666f-4d7a-884a-85b7b521610a.jpg)

