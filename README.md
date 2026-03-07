# 🌿 Custom Image Classifier with TensorFlow

Building a **Custom Image Classifier** using personal image datasets stored in **Google Drive**.

---

## Part 1: Preparing and Loading Custom Images

### Step 1 – Dataset Folder Structure

<img width="1920" height="1080" alt="Screenshot 2026-03-07 113853" src="https://github.com/user-attachments/assets/522806c3-fc05-492b-b450-71f5a53fdf3d" />

Step 2: Upload Dataset to Google Drive
<img width="1920" height="1080" alt="Screenshot 2026-03-07 114114" src="https://github.com/user-attachments/assets/1762e1ee-c385-4e8e-85af-f1e506f963b2" />

Step 3: Open Google Colab 
<img width="1920" height="1080" alt="Screenshot 2026-03-07 114640" src="https://github.com/user-attachments/assets/d1a553cb-b6b4-47de-88f7-70ed6a97b8a7" />

Step 4: Mount Google Drive in Colab 
<img width="582" height="148" alt="Screenshot 2026-03-07 114938" src="https://github.com/user-attachments/assets/0bba3907-e504-45c9-aa57-0824dc21ad3a" />

Step 5: Define Dataset Path
<img width="859" height="61" alt="Screenshot 2026-03-07 115154" src="https://github.com/user-attachments/assets/7b0b07d8-ac1d-4253-81de-77eb4bc1b87c" />

Step 6: Load Images Using TensorFlow
<img width="877" height="620" alt="Screenshot 2026-03-07 120142" src="https://github.com/user-attachments/assets/b4266942-9997-4baa-942e-24e1c0f344e6" />

Step 7: View Class Names
<img width="1821" height="109" alt="image" src="https://github.com/user-attachments/assets/a1033727-0c02-475e-b9a3-e6646f20e496" />

Part 2: Training and Evaluating the Image Classification Model
Step 1: Optimize Dataset Performance
<img width="805" height="141" alt="image" src="https://github.com/user-attachments/assets/7d786c0e-2465-4329-8d17-40ac85058bad" />

Step 2: Build the CNN Model 
<img width="817" height="355" alt="image" src="https://github.com/user-attachments/assets/cdedea06-cda4-4e3f-9cd3-ca1e5076005c" />

Step 3: Compile the Model
<img width="744" height="185" alt="image" src="https://github.com/user-attachments/assets/1283dcad-23cf-43f7-87f8-9b5ca645cdec" />

Step 4: Train the Model
<img width="1138" height="618" alt="image" src="https://github.com/user-attachments/assets/c38a9298-aa41-4c5d-96be-3302342b346c" />

Step 5: Evaluate Model Performance
<img width="786" height="168" alt="image" src="https://github.com/user-attachments/assets/8daae358-df50-4945-822b-fb3335c32cf5" />

Step 6: Test with a New Image
<img width="915" height="350" alt="image" src="https://github.com/user-attachments/assets/cfdb8d82-4ccc-4122-84f3-7e92280cd425" />

Guide Questions (Student Reflection & Explanation)
1. Dataset Preparation

Q: How did you organize your dataset in Google Drive?
I created a main folder called ImageDataset and placed the images of each plant in separate subfolders. Each subfolder represents one class or label.

Q: Why is folder structure important for TensorFlow image loading?
The folder structure is important because TensorFlow uses the folder names as labels. If the folders are organized correctly, the images will be labeled properly during training.

2. Model Training

Q: What is the role of convolutional layers in image classification?
Convolutional layers detect important features in images, such as edges, shapes, and patterns. These features help the model identify and classify the image.

Q: Why do we split data into training and validation sets?
The training set is used to teach the model, while the validation set is used to test how well the model works on new or unseen images.

3. Performance Analysis

Q: What accuracy did your model achieve?
The model achieved about 99% training accuracy, but the validation accuracy was around 47%, which means the model learned the training data too well and did not perform well on new images.

Q: How did the number of images affect the model’s performance?
Each class had around 250 images, which helped with training but was still limited. Because of this, the model had difficulty generalizing and caused overfitting.

4. Critical Thinking

Q: What challenges did you encounter while using your own dataset?
Some challenges were different image quality, slight imbalance in classes, slow loading from Google Drive, and overfitting during training.

Q: How can data augmentation improve your model?
Data augmentation creates new variations of images by flipping, rotating, or zooming them. This increases the dataset size and helps the model learn better.

5. Application

Q: Suggest a real-world application for your trained model.
The model can be used to identify plant species from images, which can help in gardening, agriculture, and plant research.

Q: How can this system be integrated into a mobile or web application?
The model can be converted using TensorFlow Lite for mobile apps or TensorFlow.js for web apps, allowing users to upload images and get predictions instantly.


Activity 3A: Improving and Evaluating a Custom Image Classifier
Title:
Enhancing Model Performance: Visualization, Overfitting Control, Data Augmentation, and Model Deployment

Part 3: Visualizing Training Results & Detecting Overfitting
Step 1: Plot Training vs Validation Accuracy and Loss
<img width="706" height="580" alt="image" src="https://github.com/user-attachments/assets/dbae13d5-6c8c-4524-a11d-4a62326e440f" />

Part 4: Applying Data Augmentation

Step 1: Create Data Augmentation Layer
<img width="501" height="175" alt="image" src="https://github.com/user-attachments/assets/bc02371c-90e5-4021-a5aa-064faea00dc8" />

Step 2: Visualize Augmented Images
<img width="640" height="699" alt="image" src="https://github.com/user-attachments/assets/2e25f945-3c70-4d73-8ed3-71cb90c30f91" />

Part 5: Reducing Overfitting Using Dropout
Step 1: Build an improved CNN Model
<img width="757" height="368" alt="image" src="https://github.com/user-attachments/assets/8a8c7419-b1b9-4a32-909e-72b7c514a9e8" />

Part 6: Compile and Train the Improved Model
Step 1: Compile Model
<img width="748" height="143" alt="image" src="https://github.com/user-attachments/assets/b119053a-ec15-4163-9b06-abe36c1c9521" />

Step 2: Train Model
<img width="884" height="572" alt="image" src="https://github.com/user-attachments/assets/72bad45a-780b-49bc-b20c-665d7b8a6d14" />

Step 3: Visualize Improved Training Results
<img width="693" height="562" alt="image" src="https://github.com/user-attachments/assets/d0856c99-49ea-4937-9d8e-71860bbc2e84" />

Part 7: Predict on New Data
Step-by-Step Procedure
<img width="822" height="261" alt="image" src="https://github.com/user-attachments/assets/8546c44e-8b3e-4f93-a6d8-97d4a4bb5455" />

Part 8: Save and Reuse the Model

Step 1: Save Model to Google Drive
<img width="711" height="63" alt="image" src="https://github.com/user-attachments/assets/94627051-0588-43fc-a3f7-df1f61c180a8" />

Step 2: Load Saved Model
<img width="819" height="79" alt="image" src="https://github.com/user-attachments/assets/36513d64-c7a2-4da2-be55-0e106416c810" />

Guide Questions (Student Explanation & Reflection)

Visualization & Overfitting

1. What signs indicated overfitting in your first model?
Overfitting was seen when the training accuracy became very high, but the validation accuracy stayed lower. This means the model learned the training images too well but could not perform well on new data.

2. How did data augmentation affect validation accuracy?
Data augmentation helped increase validation accuracy because it created more varied training images (rotated, flipped, etc.), which helped the model learn better and reduce overfitting.

Model Improvement

3. What is the purpose of dropout layers?
Dropout layers randomly turn off some neurons during training so the model does not rely too much on specific features. This helps prevent overfitting.

4. Why does data augmentation improve generalization?
Data augmentation creates different versions of the same images, which helps the model learn patterns instead of memorizing images. This allows the model to work better on new unseen data.

Performance Comparison

5. Compare accuracy before and after improvements.
Before improvements, the model had high training accuracy but lower validation accuracy.
After adding dropout and data augmentation, the validation accuracy improved and became closer to the training accuracy, showing better performance.

6. Which technique contributed most to improvement?
Data augmentation contributed the most because it increased the variety of training images, helping the model learn more robust features.

Deployment & Application

7. Why is saving the model important?
Saving the model allows us to reuse the trained model later without training it again, saving time and computing resources.

8. How can this model be deployed in a real-world system?
The model can be deployed in a web or mobile application where users upload an image and the system automatically predicts or classifies the object (for example, identifying a medical plant).

























