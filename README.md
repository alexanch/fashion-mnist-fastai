# fashion-mnist
Multi-class image classifier on the fashion MNIST dataset utilizing fastai library.
 <br />
 <br />
#### fastai can be used to solve different types of problems: collaborative filtering, vision, text, tabular. More info: [[docs.fast.ai]]( https://docs.fast.ai/applications.html#data)
#### In each case (except for collaborative filtering), the module is organized this way:
 
- **transform:**
  This sub-module deals with the pre-processing (data augmentation for images, cleaning for tabular data, tokenizing and numericalizing for text).
  
-  **data:**
   This sub-module defines the dataset class(es) to deal with this kind of data.
   
-  **models:**
   This sub-module defines the specific models used for this kind of data.
   
-  **learner:**
   When it exists, this sub-module contains functions that will directly bind this data with a suitable model and add the necessary callbacks.
  <br />
  
**Feel free to experiment here:** [[kaggle.com/alexanch]](https://www.kaggle.com/alexanch/image-classification-w-fastai-fashion-mnist)   
 <br /> <br />
Source: [[docs.fast.ai]](https://docs.fast.ai/applications.html#data) <br />
Original dataset: [[Fashion MNIST]](https://github.com/zalandoresearch/fashion-mnist)<br />
Function to original data to CSV: [[MNIST in CSV]](https://pjreddie.com/projects/mnist-in-csv/)
