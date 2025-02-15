In this AI based Food Recognition model from Food Images we have applied the following approach:

First all the necessary libraries have been imported like tensorflow, keras. For visualization purpose matplotlib has been utilized wherever needed.The images were resized and CNN is used to train the model for image classification. Feature extraction and normalization of pixel values was also done. RELU activation function has been used for real time data to capture non linearity and complex features. To prevent overfitting issues dropout is used. 
The model is then tested via parameters like accuracy, precsion, reacll, f1-score,ROC-AUC was also plotted and a very excellent result is obtained on real time data which indicates that the model is really nice one. It was then saved in a .h5 file for hosting via streamlit. A  simple website is made which accepts images as inputs and then predicts what item it is like raddish etc.

The model is scaleable and works on real time data which makes our solution a unique and holistic one.
