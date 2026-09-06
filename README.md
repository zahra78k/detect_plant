🌱 Plant Disease Classification Using YOLOv8
A computer vision project for plant disease classification and detection using YOLOv8.
The project includes dataset cleaning, image preprocessing, model training and validation, model evaluation, visualization of results, and final prediction on new plant images.
📌 Project Overview
The dataset was collected from Kaggle and prepared for the machine learning pipeline.
The main goal of this project was to build a system that can identify plant diseases from images and visualize the detected damaged areas.
The complete workflow includes:
Dataset collection from Kaggle
Image cleaning and preprocessing
Removing corrupted images
Editing and preprocessing images
Train/Test dataset preparation
YOLOv8 classification
Model training and validation
Model evaluation
Image processing
Visualization of incorrect predictions
Testing the trained model on new images
Detection and visualization of damaged areas
Generating plots and final reports
🧹 Data Cleaning & Preprocessing
Before training the model, the dataset was carefully prepared.
The preprocessing stage included:
Detecting and removing corrupted images
Cleaning the dataset
Editing and preprocessing images
Preparing images for model training
Organizing the dataset into training and testing sets
🤖 Model
YOLOv8 was used for the plant disease classification task.
The model was trained on the cleaned dataset and evaluated using a validation set containing 10,872 images.
📊 Model Performance
The model achieved the following results on the validation dataset:
Metric Score
Validation Images 10,872
Accuracy 99.71%
Precision 99.72%
Recall 99.71%
F1-score 99.71%
These results demonstrate strong classification performance on the validation dataset.
📈 Training Performance
Training and validation metrics were monitored throughout the training process.
Loss
The training loss and validation loss showed a decreasing trend during training, indicating that the model was learning effectively and improving its performance.
Accuracy
The training accuracy and validation accuracy showed an increasing trend during training, demonstrating progressive improvement in classification performance.
The training curves were saved as part of the final project results.
🧮 Confusion Matrix
A confusion matrix was generated to evaluate the classification performance across different plant disease classes.
It provides a detailed view of correct and incorrect predictions for each class.
❌ Error Analysis
Several incorrectly predicted images were extracted and displayed for further analysis.
This error analysis helped identify cases where the model had difficulty distinguishing between different plant disease classes.
🖼️ Image Processing
Image processing techniques were used as part of the project pipeline.
For individual image testing, the trained model was used to analyze a new plant image.
If a damaged or diseased area was detected, the affected region was highlighted using a bounding box.
The detected damaged regions were also processed and visualized to make the affected areas easier to identify.
🔍 Single Image Prediction
The final trained model was tested on individual plant images.
The prediction pipeline can:
Receive a new plant image
Process the image
Predict the plant condition
Detect damaged areas
Display bounding boxes around detected regions
Highlight the detected damaged areas
Generate the final prediction result
📊 Results Visualization
Several visualizations were created during the project, including:
Confusion Matrix
Training Loss Curve
Validation Loss Curve
Training Accuracy Curve
Validation Accuracy Curve
Incorrect Predictions
Bounding Box Detection Results
Final Prediction Results
🛠️ Technologies & Libraries
Python
YOLOv8
NumPy
Pandas
OpenCV
Scikit-learn
Seaborn
Matplotlib
Final Report
A final report was generated containing:
Dataset preprocessing information
Model performance metrics
Confusion Matrix
Training and validation curves
Incorrect prediction analysis
Single image prediction results
Bounding box visualizations
Final project results
👩🏻‍💻 Author
Zahra Karimfard
AI Developer | Python | Machine Learning | Computer Vision
