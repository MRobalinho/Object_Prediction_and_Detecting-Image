# Object_Prediction_and_Detecting-Image
 
## 1. Preparation
### 1.1 Prerequisite Dependencies
As described by on ImageAI’s Github, multiple Python dependencies need to be installed:

>Tensorflow 
>Numpy 
>SciPy 
>OpenCV 
>Pillow 
>Matplotlib 
>h5py 
>Keras


All packages can be easily installed by command:

>pip3 install PackageName


### Afterwards, ImageAI can be installed by a single command:

>pip3 install https://github.com/OlafenwaMoses/ImageAI/releases/download/2.0.1/imageai-2.0.1-py3-none-any.whl

### 1.2 CNN Models

Two models are adopted as in the examples prediction and detection.


>Prediction : resnet50_weights_tf_dim_ordering_tf_kernels.h5 - can be downloaded at fchollet’s deep-learning-models here 
>Detection: resnet50_coco_best_v2.1.0.h5 - can be downloaded at fizyr’s keras-retinanet here

## 2.1 Prediction
### Simple examples are given at here

ImageAI provides 4 different algorithms and model types to perform image prediction. To perform image prediction on any picture, take the following simple steps. The 4 algorithms provided for image prediction include SqueezeNet, ResNet, InceptionV3 and DenseNet. Each of these algorithms have individual model files which you must use depending on the choice of your algorithm. To download the model file for your choice of algorithm, click on any of the links below:

>SqueezeNet (Size = 4.82 mb, fastest prediction time and moderate accuracy)
>ResNet50 by Microsoft Research (Size = 98 mb, fast prediction time and high accuracy)
>InceptionV3 by Google Brain team (Size = 91.6 mb, slow prediction time and higher accuracy)
>DenseNet121 by Facebook AI Research (Size = 31.6 mb, slower prediction time and highest accuracy)
