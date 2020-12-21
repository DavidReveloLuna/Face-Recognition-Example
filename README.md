# Face-Recognition-Example

## Preparación del entorno
    $ conda create -n Face anaconda python=3.7.7
    $ conda activate Face
    $ conda install ipykernel
    $ python -m ipykernel install --user --name Face --display-name "Face"
    $ conda install tensorflow-gpu==2.1.0 cudatoolkit=10.1
    $ pip install tensorflow==2.1.0
    $ pip install jupyter
    $ pip install keras==2.3.1
    $ pip install numpy scipy Pillow cython matplotlib scikit-image opencv-python h5py imgaug IPython[all]
    
### Librerias para Face-recognition

    $ pip install cmake
    $ conda install -c conda-forge dlib
    $ pip install face_recognition
    $ pip install deepface
    
### Código de ejemplo - tiempo real
   
[Face_example.ipynb](https://github.com/DavidReveloLuna/Face-Recognition-Example/blob/master/Face_example.ipynb)
   
    * Face recognition
    * Face location
    * Landmarks
    * Real-Time landmarks detection
    * Real-Time face encoding 
    * Prediction of emotion, gender, age, race
    * Real-Time emotion recognition
    

### Download Pre-trained models
        
   [Facial_expression_model_weights](https://drive.google.com/uc?id=13iUHHP3SlNg53qSuQZDdHDSDNdBP9nwy)

   [Age_model_weights](https://drive.google.com/uc?id=1YCox_4kJ-BYeXq27uUbasu--yz28zUMV)
     
   [Gender_model_weights]( https://drive.google.com/uc?id=1wUXRVlbsni2FN9-jkS_f4UTUrm1bRLyk)     
       
   [Race_model_single_batch.zip ](https://drive.google.com/uc?id=1nz-WDhghGQBC4biwShQ9kYjvQMpO6smj )
    
### Landmarks

![Landmarks](https://github.com/DavidReveloLuna/Face-Recognition-Example/blob/master/assets/foto1.png)

### Predicción

![Landmarks](https://github.com/DavidReveloLuna/Face-Recognition-Example/blob/master/assets/foto2.png)

## Agradecimientos
Author: Face_recognition
[Adam Geitgey](https://pypi.org/project/face-recognition/)

Author: DeepFace
[Sefik Ilkin Serengil](https://pypi.org/project/deepface/)

