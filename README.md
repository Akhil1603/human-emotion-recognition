# human-emotion-recognition
 Built a CNN model using Python, TensorFlow, and Keras for multi-class classification of facial expressions and emotions, including data loading, preprocessing, model architecture configuration, performance evaluation, and real-time prediction capabilities.
 
**Introduction**
The provided Jupyter Notebook, "HumanEmotionRecognition.ipynb," focuses on the task of human
emotion recognition using a deep learning model. The report outlines the code and workflow within
the notebook.

**Setup and Configuration**
The notebook starts by configuring various parameters for the model. It defines constants such as
batch size, image size, learning rate, and more. It also specifies the directories for the training and
validation datasets, along with the class names for emotions.

**Data Loading and Preprocessing**
The data loading and preprocessing are performed using TensorFlow. Training and validation datasets
are loaded using TensorFlow's data pipeline. Data augmentation techniques like random flipping and
rotation are applied to the training dataset. Additionally, the data is normalized to a scale of [0, 1].

**Custom R2 Metric**
The notebook introduces a custom evaluation metric, R-squared (R2), to assess the model's
performance. R2 measures how well the model's predictions fit the actual labels.

**Model Architecture**
The model architecture is defined using TensorFlow's Keras API. It comprises convolutional layers,
max-pooling layers, and fully connected (dense) layers. Dropout and L2 regularization are used to
mitigate overfitting. The model's goal is to classify images into three emotions: "angry," "happy," and
"sad."

**Model Compilation**
The model is compiled with the Adam optimizer and categorical cross-entropy loss. Additionally, it is
evaluated using multiple metrics, including categorical accuracy and the custom R2 metric.

**Training and Evaluation**
The model is trained on the training dataset over a specified number of epochs. Training progress is
monitored using callbacks. After training, the model's performance is evaluated on the validation
dataset, and metrics such as validation loss, accuracy, and R2 score are reported.

**Prediction**
The notebook includes a section for making predictions. It provides a function to preprocess input
images, and a function to predict the emotion in an image. The predicted emotion is displayed along
with the input image.

**Conclusion**
The provided Jupyter Notebook presents a comprehensive workflow for human emotion recognition.
It encompasses data loading, preprocessing, model creation, training, evaluation, and prediction. The
inclusion of data augmentation, custom metrics, and model regularizations enhances the robustness
of the model. This notebook can serve as a valuable resource for emotion recognition tasks.
---
This report summarizes the key aspects of the provided notebook, offering a clear and concise
overview of the tasks performed and the purpose of the code.
