# Deep-learning
Deep learning (also known as deep structured learning or hierarchical learning) is part of a broader family of machine learning methods based on artificial neural networks. Learning can be supervised, semi-supervised or unsupervised.

### Installation of Keras
Linux or mac OS users, go to your project root directory and type the below command to create virtual environment:
     
     python3 -m venv kerasenv
   
### Windows

Windows user can use the below command,

     py -m venv keras  
### Numpy

     pip install numpy 
     
     ```Collecting numpy 
        Downloading 
     https://files.pythonhosted.org/packages/cf/a4/d5387a74204542a60ad1baa84cd2d3353c330e59be8cf2d47c0b11d3cde8/ 
        numpy-3.1.1-cp36-cp36m-macosx_10_6_intel.
     macosx_10_9_intel.macosx_10_9_x86_64. 
        macosx_10_10_intel.macosx_10_10_x86_64.whl (14.4MB) 
           |████████████████████████████████| 14.4MB 2.8MB/s```     


### Pandas 
   If you want to draw some conclusions based on the facial expressions or generate active sentiments u may use pandas library.
     
     pip install pandas
     
     ```Collecting pandas 
        Downloading 
     https://files.pythonhosted.org/packages/cf/a4/d5387a74204542a60ad1baa84cd2d3353c330e59be8cf2d47c0b11d3cde8/ 
     pandas-3.1.1-cp36-cp36m-macosx_10_6_intel.
     macosx_10_9_intel.macosx_10_9_x86_64. 
        macosx_10_10_intel.macosx_10_10_x86_64.whl (14.4MB) 
           |████████████████████████████████| 14.4MB 2.8MB/s```
           
### CNN architecture and training
     The CNN architecture used here is a variant of the inception architecture [2]. More precisely, it is a variant of the NN4 architecture described in [1] and identified as nn4.small2 model in the OpenFace project. This article uses a Keras implementation of that model whose definition was taken from the Keras-OpenFace project. The architecture details aren’t too important here, it’s only useful to know that there is a fully connected layer with 128 hidden units followed by an L2 normalization layer on top of the convolutional base. These two top layers are referred to as the embedding layer from which the 128-dimensional embedding vectors can be obtained. The complete model is defined in model.py and a graphical overview is given in model.png. A Keras version of the nn4.small2 model can be created with create_model().
      
### Example of the working model
  ![Training on Celeb Faces](https://i1.wp.com/sefiks.com/wp-content/uploads/2020/02/deepface-tests.png?ssl=1)
