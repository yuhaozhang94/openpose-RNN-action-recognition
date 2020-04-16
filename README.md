# humanpose-rnn-action-recognition
We implemented a deep neural network to predict human actions by modifying the gait recognition model by Marian Margeta (https://github.com/marian-margeta/gait-recognition). We extracted the spatial features of the human poses of each frame and extract their temporal features by running a Recurrent Neural Network. At last, we classify the human action with a Logistic Regression Model. We were able to achieve an accuracy of 94.87% on the G3D dataset (http://dipersec.kingston.ac.uk/G3D/G3D.html). 
