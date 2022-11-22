# Team Info

CMPE-258 Fall 2022 Team Project



# Description

# Dataset

TODO: LFW link & info

# 

## How to run the notebook1 for evaluating the Facenet on FLW？

1. We recommend running the note book in **Google Colab**。

2. Before running the code, please install MTCNN python package, the command provided in the first bock.
```sh
!pip install mtcnn
```

3. Please authorize the Colab to connect with a Google drive.
```sh
	from google.colab import drive
	drive.mount('/content/drive')
```

4. Set the “basepath” value to your project base directory in the google drive.
```sh
	basepath = '/content/drive/My Drive/cmpe258/lfw' 
    #This is an example, please substiute it with your own path
```
5. Put the pre-trained Facenet model weights into ”{basepath}/model“, and the notebook will load the model from this path.

6. Run the notebook.

7. The step “Use MTCNN face detector and Facenet embedding to get distance from 400 image pairs” may take hours.  Please be patient and keep the kernel alive until it finished.

