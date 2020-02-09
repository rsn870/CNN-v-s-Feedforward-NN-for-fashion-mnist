These days Convolutional Networks are used a great deal for image classification . This architechture 
inspired by the neuronal architechture present in the visual cortex of mammals works so weel because
it assumes an underlying spatial relationship that exists between points on a grid i.e suppose there is a 2D image
we can represnt it as a matrix of pixels with ecah element of the matrix having a value in the range(0,255 ) (255 incl) 
Now suppose a particluar point of an image is colored say grey then points closer to it are likely to be colored grey as well
this is what we mean by an underlying spatial relationship . Similarly another capability present in CNNs are the 
capability of 'translational invariance' suppose there is a banana in the top left corner of the image If instead of the
top left corner the banana had been present in the bottom-right corner (say) even then we knbow that it's still a banana 
even though it has been shifted fromn its position and the CNN also classifies it accordingly . The final advantage of CNN
is the capability to have really really deep models as compared to various other architechtures .

We investigate all these capabilities of CNNs and more by using the fashion _mnist datset a variant of the mnist datset that
can be regarded as the "hello world" of computer vision .

We compare different CNN architechtures with a classic feed forward architechture in a manner through which the differences 
can be clearly established .

The code is written in a .ipynb (jupyter notebook) file using  tensorflow 2.0 with keras backend as the support; tensorboard has been used for visualisation purposes 
as well but this can be omitted . Standard libraries like numpy and matplotlib have also been used to get some concrete
results that can be appreciated by the reader .

Happy Coding !

