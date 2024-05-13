# X-AI-Scene-Classification-and-GradCam-Visualization-With-ResNet-18




In this project, our objective is to construct and train a Deep Convolutional Neural Network (CNN) alongside Residual Blocks for the purpose of identifying the scenery type depicted in an image. Furthermore, we'll employ a method called Gradient-Weighted Class Activation Mapping (Grad-CAM) to visually depict the areas of interest within the inputs. This visualization technique aids in elucidating the decision-making process of our CNN models, shedding light on their cognitive processes.

Datasets are used from Kaggle.com for buildings, forest, oceans, glaciers etc

All the images and outputs of the models are given in the images and data folder itself

Some images were not properly visualised by the Grad-Cam, it could have been developed if we would have used a better epoch size and a lower validation accuracy with improvemnet in validation loss.


Future scopes of the Project Include-


Try other approaches to explain CNN outputs such as: Activations Visualization, Vanilla Gradients, Occlusion Sensitivity, CNN Fixations, and Class Activation Mapping (CAM).

Apply Transfer Learning



References :

Ahmed, R. (n.d.). Explainable AI: Scene Classification and GradCam Visualization [MOOC]. Coursera. https://www.coursera.org/projects/scene-classification-gradcam

Explainable AI. IBM. (n.d.). https://www.ibm.com/watson/explainable-ai.

He, K., Zhang, X., Ren, S., & Sun, J. (2016). Deep Residual Learning for Image Recognition. 2016 IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 770–778.

King, J., Kishore, V., Ranalli, F. (2017). Scene classification with Convolutional Neural Networks.

Rosebrock, A. (2020, March 9). Grad-CAM: Visualize Class Activation Maps with Keras, TensorFlow, and Deep Learning. PyImageSearch. Retrieved September 10, 2021, from https://www.pyimagesearch.com/2020/03/09/grad-cam-visualize-class-activation-maps-with-keras-tensorflow-and-deep-learning/.