# STATAP
Object detection
Les liens pour la doc :

https://pytorch.org/vision/stable/_modules/torchvision/models/detection/faster_rcnn.html

https://pytorch.org/vision/stable/models.html#faster-r-cnn

https://pytorch.org/docs/stable/_modules/torch/utils/data/dataloader.html

https://pytorch.org/tutorials/intermediate/torchvision_tutorial.html

Transfer Learning : 

https://pytorch.org/vision/stable/_modules/torchvision/models/resnet.html#resnet50

https://pytorch.org/vision/stable/models.html#torchvision.models.resnet50

https://arxiv.org/pdf/1512.03385.pdf

https://pytorch.org/tutorials/beginner/finetuning_torchvision_models_tutorial.html

https://pytorch.org/tutorials/beginner/finetuning_torchvision_models_tutorial.html#set-model-parameters-requires-grad-attribute

Ici on trouve les valeurs par défaut de image_mean:= [0.485, 0.456, 0.406] et std_mean := [0.229, 0.224, 0.225]
https://github.com/pytorch/vision/blob/75f5b57e680549d012b3fc01b356b2fb92658ea7/torchvision/models/detection/faster_rcnn.py#L227-L230


Arguments:
        pretrained (bool): If True, returns a model pre-trained on COCO train2017
        progress (bool): If True, displays a progress bar of the download to stderr
        pretrained_backbone (bool): If True, returns a model with backbone pre-trained on Imagenet
        num_classes (int): number of output classes of the model (including the background)
        trainable_backbone_layers (int): number of trainable (not frozen) resnet layers starting from final block.
            Valid values are between 0 and 5, with 5 meaning all backbone layers are trainable.
