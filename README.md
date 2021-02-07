# Electrothon-3.0

We have used pretrained networks, namely DenseNet, Incetion, Inception-ResNet, VGG, and ResNet for the detection of covid-19, pneumonia from the analysis of chest X-ray images of patients. For each network, we have added two dense layers and trained them on the dataset. The weights of these layers for each network are present in the '.rar' files. Visualisations.ipynb shows the Saliency map and GradCAM for a particular X-ray image of a patient diagnosed with covid-19. Deep patterns.ipynb shows the evolution of complex features learned by the convolutional network which may be key to understand the functioning of the black-box model. Ensemble.ipynb gives us ways to improve the generalisability of the pretrained models by proposing a soft-voting classifier and a stacking ensemble. Feature disentanglement.ipynb gives us a proof that the model extracts excellent features that are generalisable and robust. This implies that the model can perform well even on unseen data, though it is trained on very few data samples!

In the notebooks, 
Class 0 represents 'Covid'
Class 1 represents 'Normal'
Class 2 represents 'Pneumonia'

External references:
1) https://github.com/keisen/tf-keras-vis/blob/master/examples/attentions.ipynb
2) https://www.tensorflow.org/tutorials/generative/deepdream
3) https://arxiv.org/pdf/2004.13175.pdf 
