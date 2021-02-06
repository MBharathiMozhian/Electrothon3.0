# Electrothon-3.0

We have used pretrained networks, namely DenseNet, Incetion, Inception-ResNet, VGG, and ResNet for the detection of covid-19, pneumonia from the analysis of chest X-ray images of patients. For each network, we have added two dense layers and trained them on the dataset. The weights of these layers for each network are present in the '.rar' files. Visualisations.ipynb shows the Saliency map and GradCAM for a particular X-ray image of a patient diagnosed with covid-19. Deep patterns.ipynb shows the evolution of complex features learned by the convolutional network which may be key to understand the functioning of the black-box model. Ensemble.ipynb gives us ways to improve the generalisability of the pretrained models by proposing a soft-voting classifier and a stacking ensemble. 

External references:
1) https://github.com/keisen/tf-keras-vis/blob/master/examples/attentions.ipynb
2) https://www.tensorflow.org/tutorials/generative/deepdream
3) https://arxiv.org/pdf/2004.13175.pdf 
