# Project-4-Group-8

## Optimisation
Firstly, we decreased the first hidden layer neurons from 7 to 3, the second hidden layer neurons from 14 to 6.

Secondly, we added the third hidden layer neurons.

Thirdly, we used different activation function for the hidden layer, from ReLU to Tanh.

Finally, Tanh is better than ReLu, and three hidden layers better than two. the best accuracy was composed of Tanh and 3/6/12 layer

### Function **ReLU**
+ 7/14:  
33/33 - 1s - loss: 0.3537 - accuracy: 0.8835 - 844ms/epoch - 26ms/step  
Loss: 0.35365232825279236, Accuracy: 0.8834951519966125
+ 7/14/21:  
33/33 - 1s - loss: 0.7113 - accuracy: 0.8854 - 505ms/epoch - 15ms/step  
Loss: 0.7113155722618103, Accuracy: 0.8854368925094604
+ 3/6:  
33/33 - 1s - loss: 0.3223 - accuracy: 0.8961 - 934ms/epoch - 28ms/step  
Loss: 0.3223118185997009, Accuracy: 0.8961164951324463
+ 3/6/12:  
33/33 - 1s - loss: 0.2780 - accuracy: 0.8786 - 842ms/epoch - 26ms/step  
Loss: 0.2780188024044037, Accuracy: 0.8786407709121704
### Function **Tanh**
+ 3/6:  
33/33 - 1s - loss: 0.2194 - accuracy: 0.8990 - 753ms/epoch - 23ms/step  
Loss: 0.2194284200668335, Accuracy: 0.8990291357040405
+ 3/6/12:  
33/33 - 1s - **loss: 0.2335 - accuracy: 0.9029** - 567ms/epoch - 17ms/step  
Loss: 0.23351119458675385, Accuracy: 0.9029126167297363
+ 7/14/21:  
33/33 - 1s - loss: 0.6689 - accuracy: 0.9000 - 895ms/epoch - 27ms/step  
Loss: 0.6688849925994873, Accuracy: 0.8999999761581421
