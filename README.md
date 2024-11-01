# CSST106-CS4A
# Presentation Development:


https://github.com/user-attachments/assets/b997a4b7-c42c-48c7-af0b-6a7991bbdb8c


# **What is Computer Vision?**
Computer Vision is a field of artificial intelligence that allows computers to "see" and interpret the world through images and videos. By using deep learning algorithms, machines can recognize objects, track movements, and analyze visual data, much like how humans use their eyes. This technology is widely used in areas such as self-driving cars, facial recognition, medical imaging, and surveillance systems.

# **What is Image Processing?**
Image processing is a technique used to improve and manipulate images, making it easier for computers to understand and analyze them. It involves tasks like reducing noise, adjusting brightness and contrast, detecting edges, and dividing images into segments. These steps help prepare images for further analysis in applications like object recognition, medical imaging, and facial recognition systems. Image processing is a crucial part of computer vision, enabling AI to extract useful information from visual data.

# **How do Computer Vision and Image Processing work together?**
Computer Vision and Image Processing collaborate to enable machines to effectively interpret and analyze visual data. Image processing serves as the initial step, where raw images or video frames undergo enhancement and manipulation through techniques such as noise reduction, contrast enhancement, and edge detection. These methods refine and prepare the visual data for further analysis. Once the image processing is complete, computer vision algorithms take over, extracting critical features and analyzing the data to recognize objects, track movements, and interpret scenes.

This synergy allows computer vision systems to make informed decisions based on the processed visual information. For example, in a retail environment, image processing might be used to clean and sharpen surveillance footage from security cameras, reducing glare and improving clarity. Computer vision algorithms then analyze the refined footage to detect suspicious behavior, monitor foot traffic, and analyze customer interactions with products, helping store managers enhance security and improve customer service.
 
# 3 Types of Image Processing Techniques

__I. Edge Detection__

* **Edge detection** is a technique used to identify boundaries within an image by highlighting areas where there is a significant change in intensity. This process helps in distinguishing different objects and structures by detecting discontinuities in brightness. By emphasizing the edges, it allows for easier identification and analysis of shapes, contours, and features within the image. Edge detection is fundamental in various applications, such as object recognition, image segmentation, and computer vision, as it simplifies the image data while preserving essential structural information.

**Example:**
In a manufacturing process, edge detection is used to ensure the quality of products, such as identifying defects in metal parts or ensuring proper alignment of components.

__How Edge Detection Helps:__

1.	__Image Capture:__ Cameras or sensors capture images of manufactured parts on a production line.
2.	__Edge Detection:__ The edge detection algorithm processes these images to identify the boundaries of each part and check for any deviations. For example, it can detect misalignments, missing sections, or irregularities in the edges of metal parts.
3.	__Defect Identification:__ By analyzing the detected edges, the system can spot defects like scratches, dents, or incorrect dimensions. The algorithm helps in distinguishing between acceptable and defective parts.
4.	__Quality Control:__ The detected defects are flagged, and defective parts are removed from the production line. This ensures that only high-quality products reach customers, reducing the likelihood of product failures and increasing customer satisfaction.

**AI applications of edge detection:**

1.	__Object Detection:__  Identifies and outlines objects in images for tasks like facial recognition and vehicle tracking.
2.	__Image Segmentation:__ Divides images into regions for medical imaging and geographic analysis.
3.	__Facial Recognition:__ Detects facial features to verify identities.
4.	__Image Enhancement:__ Sharpens images to improve clarity for AI models.
5.	__Robotic Vision:__ Helps robots navigate and interact with their environment by detecting edges.
6.	__Augmented Reality:__ Aligns virtual objects with real-world features by detecting edges.

 
**II. Image Segmentation**

* **Image Segmentation** is a process used to partition an image into distinct regions or segments based on certain criteria, such as color, intensity, or texture. This technique is crucial for simplifying the representation of an image or making it more meaningful and easier to analyze. By dividing an image into meaningful segments, image segmentation facilitates various applications in computer vision, medical imaging, and object recognition.

**Example:** In medical imaging, image segmentation is employed to identify and isolate different anatomical structures, such as organs or tumors, from MRI or CT scans.

**How Image Segmentation Helps:**

1.	__Image Capture:__ High-resolution images are captured through imaging devices, such as MRI machines, CT scanners, or cameras.
2.	__Segmentation Algorithm:__ The segmentation algorithm processes the captured images to divide them into segments or regions based on predefined criteria. For example, in a CT scan, it might segment the image into regions representing different tissues or organs.
3.	__Region Analysis:__ Each segmented region is analyzed to identify and extract specific features or structures. This helps in distinguishing between different tissues or identifying abnormal regions, such as tumors.
4.	__Application and Decision-Making:__ The segmented regions are used for further analysis or decision-making. For instance, in medical imaging, this might involve diagnosing diseases, planning surgeries, or monitoring disease progression.

**AI Applications of Image Segmentation:**

1.	__Medical Imaging:__ Enhances the accuracy of diagnosis by isolating and analyzing different anatomical structures, such as organs, tumors, or lesions.
2.	__Autonomous Vehicles:__ Helps in detecting and classifying objects on the road, such as vehicles, pedestrians, and traffic signs, for safe navigation.
3.	__Object Recognition:__ Identifies and categorizes objects within an image, which is useful for applications in robotics and computer vision.
4.	__Agricultural Analysis:__ Segments images of crops or soil to assess health, growth, or detect pests and diseases.
5.	__Satellite Imagery:__ Analyzes and classifies different land cover types or changes in the environment from satellite images.
6.	__Augmented Reality:__ Improves the integration of virtual elements with the real world by accurately segmenting and understanding the physical environment.

**III. Convolutional Neural Networks (CNNs)**

* **Convolutional Neural Networks (CNNs)** are deep learning models designed for processing images and structured grid data. Inspired by the visual cortex, CNNs excel at detecting spatial patterns through layers of convolutional filters.

**Key Components:**
1.	__Convolutional Layers:__ Apply filters to detect features like edges and textures.
2.	__Activation Functions:__ Introduce non-linearity (e.g., ReLU) to capture complex patterns.
3.	__Pooling Layers:__ Reduce dimensions while retaining key information (e.g., max pooling).
4.	__Fully Connected Layers:__ Flatten and connect features for final classification or regression.
5.	__Normalization Layers:__ Improve training stability (e.g., batch normalization).

**Example:** In image classification, CNNs can identify objects in an image, like recognizing a cat or dog.

**Applications:**
1.	__Image Classification:__ Categorizes images (e.g., photo tagging).
2.	__Object Detection:__ Finds and locates objects (e.g., in autonomous vehicles).
3.	__Image Segmentation:__ Divides images into regions (e.g., medical imaging).
4.	__Facial Recognition:__ Identifies facial features (e.g., security systems).
5.	__Image Generation:__ Creates new images based on learned features (e.g., artistic style transfer).

# Case Study Overview: *REMINI* 
**Remini** is an AI-powered photo enhancement app that focuses on improving the quality of old, blurry, or low-resolution images. 

![rem](https://github.com/user-attachments/assets/96c75bf4-dcff-44aa-b123-3f94ce0e15b1)

* **Image Analysis
:** When you upload an image, Remini starts by preprocessing it, adjusting the brightness, contrast, and noise levels to set the stage for further analysis. Following this, the app employs deep learning models to perform feature extraction, analyzing key elements such as edges, textures, and patterns within the image.
* **Deep Learning Models:** Remini primarily utilizes Convolutional Neural Networks (CNNs), which are highly effective at recognizing and interpreting patterns in images. These networks are trained on extensive datasets of high-resolution images, allowing them to learn how to enhance image quality. Additionally, the app uses super-resolution techniques, which involve generating high-resolution images from their low-resolution counterparts. This process predicts and incorporates details that were absent in the original image.
* **Enhancement Techniques:** The AI model employed by Remini is adept at image restoration, reconstructing missing details and correcting distortions caused by blurriness or aging. It sharpens edges, restores textures, and reduces noise to improve the overall quality of the image. The app also performs upscaling by increasing the image resolution and filling in missing details based on information learned from similar images during the training phase.
* **Post-Processing:** After the AI model has processed the image, Remini applies additional fine-tuning adjustments to further enhance its appearance. This post-processing phase may include color correction, contrast adjustment, and sharpening to refine the image. Some versions of the app also allow users to provide feedback or make manual adjustments to achieve even better results.
* **Continuous Learning:** Remini’s AI models are continuously updated and refined based on user interactions and new data. This ongoing process of model updates helps to improve the enhancement techniques, ensuring that the app maintains high-quality results and adapts to new challenges in image processing.

# Importance of Effective Image Processing in AI
Effective image processing in AI offers several significant advantages. It enhances accuracy by using advanced algorithms to detect defects with precision, ensuring high-quality standards. Real-time processing capabilities enable immediate feedback and dynamic adjustments, optimizing production efficiency and minimizing waste. Consistency in product quality is achieved through uniform analysis of shape, size, and color, reducing variability. Automated sorting mechanisms streamline the production process by efficiently separating defective products from acceptable ones. Additionally, the system’s adaptability to new defect types and evolving quality standards ensures ongoing effectiveness. Data-driven insights provided by image processing also facilitate continuous improvements and proactive management of production issues.
 
# Benefits of effective image processing in AI:

1.	__Improved Accuracy:__ Advanced image processing algorithms ensure precise detection of defects and adherence to quality standards, leading to higher product quality and fewer errors.
2.	__Enhanced Efficiency:__ Real-time analysis allows for immediate feedback and adjustments, optimizing production processes and reducing waste.
3.	__Consistent Quality:__ Automated sorting and uniform measurement of product attributes ensure consistent quality and minimize variability across the production line.

# Reflection on Learning
This activity deepened my understanding of how vital image processing is in enhancing AI applications, particularly in maintaining quality control in industries like potato chip production. Exploring different image processing techniques and their applications highlighted the importance of combining traditional methods with advanced AI models, such as Convolutional Neural Networks (CNNs), to achieve accurate analysis. This approach addresses challenges like detecting defects and making real-time adjustments. I learned how AI-powered image processing can be scaled and adapted to various production environments, improving efficiency, reducing waste, and ensuring consistently high-quality products.

# Extension Activity:
**Emerging Technique: Panoptic Segmentation with PETS (Panoptic End-to-End Transformers)**
Panoptic End-to-End Transformers (PETS) represent a cutting-edge approach in the field of image processing and computer vision. PETS are designed for efficient 3D scene understanding by combining object detection, instance segmentation, and semantic segmentation into a unified framework. This approach uses transformers to directly model the global context of the scene, significantly improving the accuracy and efficiency of panoptic segmentation tasks.

**Key Features**
1.	__Unified Framework:__ PETS integrate multiple tasks (object detection, instance segmentation, and semantic segmentation) into a single model, streamlining the process of scene understanding. This contrasts with traditional methods that use separate models for each task, often leading to inconsistencies and increased computational costs.
2.	__Global Context Modeling:__ By leveraging transformer architecture, PETS can capture long-range dependencies across the entire image, allowing for a more holistic understanding of complex scenes. This is particularly beneficial for segmenting overlapping objects and understanding spatial relationships.
3.	__End-to-End Training:__ The transformer-based approach allows for end-to-end training, simplifying the learning pipeline and reducing the need for post-processing steps. This results in faster inference times and more robust performance in various conditions.
Potential Impact on Future AI Systems
1.	__Enhanced Autonomous Systems:__ PETS can significantly improve the perception capabilities of autonomous systems, such as self-driving cars and drones, by providing more accurate and reliable scene understanding. This could lead to safer navigation and better decision-making in dynamic environments.
2.	__Advanced Augmented Reality (AR) Applications:__ With their ability to accurately segment and understand complex scenes, PETS can enhance AR applications by enabling more realistic interactions between virtual objects and real-world environments. This could revolutionize fields such as gaming, remote assistance, and virtual training.
3.	__Improved Medical Imaging Analysis:__ PETS can also be applied to medical imaging, where precise segmentation of anatomical structures is crucial. By providing accurate and efficient segmentation, PETS could aid in diagnosis, surgical planning, and personalized treatment strategies.
4.	__Efficiency in Content Creation:__ For industries like film, animation, and virtual content creation, PETS can streamline the process of scene understanding and segmentation, reducing the time and effort required to produce high-quality visual effects and animations.
__Conclusion__

__PETS (Panoptic End-to-End Transformers)__ represent a significant leap forward in the field of image processing, offering a unified and efficient approach to 3D scene understanding. By leveraging the power of transformers, PETS can enhance the accuracy and efficiency of autonomous systems, AR applications, medical imaging, and content creation, paving the way for more advanced and intelligent AI systems in the future.

# Hands-On Exploration
**Case Study Selection: AI application:ParaScript**

**Signature Fraud Detection**
* SignatureXpert.AI® is a signature forgery detection software that provides signature verification with unprecedented accuracy. It enables signature authentication in applications including check processing, loan origination, voting by mail, petitions, and countless other uses where it is crucial to prevent signature fraud. SignatureXpert.AI provides the highest degree of accuracy for any document type that requires signature validation, and it exceeds the performance of other signature forgery detection software on the market.

**Signature Analysis**
* SignatureXpert.AI’s advanced functionality helps to prevent signature fraud by combining multiple verifiers to analyze dozens of signature features and can use multiple references to differentiate between natural anomalies and true irregularities that indicate fraud.

**Implementation Creation**
Convolutional Neural Network (CNN) is a type of deep learning model specifically designed for processing and analyzing visual data, such as images. It is highly effective in tasks like image classification, object detection, and other image recognition problems due to its ability to automatically learn spatial hierarchies of features from input images.

1. **Redundant Code for Loading and Normalizing Images:** The data loading and normalization sections are repeated. You can consolidate these steps to avoid redundancy.

2. **Reshaping Training and Testing Data:** The reshaping steps for X_train and X_test are done using dummy data. It's better to use the actual data loaded earlier to avoid mismatches.

3. **Consistency in Imports:** Some imports are repeated unnecessarily. Grouping all imports at the top of the script is usually a good practice.

4. **Fix in Reshaping the Test Set:** The reshaping of X_test uses X_train instead of X_test, which seems like a copy-paste error.

# Import Libraries

`import numpy as np`

`import pandas as pd`

`import matplotlib.pyplot as plt`

`import cv2`

`import os`

`from sklearn.model_selection import train_test_split`

`import tensorflow as tf`

`from tensorflow.keras.layers import Conv2D, MaxPooling2D, Dense, Flatten, Dropout`

`from tensorflow.keras.models import Sequential`

`from tensorflow.keras.preprocessing.image import ImageDataGenerator`

# Load the real and forged signature datasets
`real_path = '/content/drive/MyDrive/dataset/orininal dataset'`

`forge_path = '/content/drive/MyDrive/dataset/fraud dataset'`

`real_images = []`

`for img_name in os.listdir(real_path):`
   
    img = cv2.imread(os.path.join(real_path, img_name), cv2.IMREAD_GRAYSCALE)
    real_images.append(img)

`real_images = np.array(real_images, dtype=object)`

`forge_images = []`

`for img_name in os.listdir(forge_path):`

    `img = cv2.imread(os.path.join(forge_path, img_name), cv2.IMREAD_GRAYSCALE)`
    
    `forge_images.append(img)`

`forge_images = np.array(forge_images, dtype=object)`

# Spliting the Training and Testing Images

`real_labels = np.zeros(real_images.shape[0])`

`forge_labels = np.ones(forge_images.shape[0])`

`X = np.concatenate((real_images, forge_images), axis=0)`

`y = np.concatenate((real_labels, forge_labels), axis=0)`

`X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)`

# Loading the Data and Normalizing it
`import cv2`
 
`import numpy as np`

# load the dataset
`real_path = '/content/drive/MyDrive/dataset/orininal dataset'`

`forge_path = '/content/drive/MyDrive/dataset/fraud dataset'`

# set the image size to 128x128
`img_size = (128, 128)`

`real_images = []`

`for img_name in os.listdir(real_path):`
    
    img = cv2.imread(os.path.join(real_path, img_name), cv2.IMREAD_GRAYSCALE)
    img = cv2.resize(img, img_size)
    real_images.append(img)

`real_images = np.array(real_images)`

`forge_images = []`

`for img_name in os.listdir(forge_path):`
    
    img = cv2.imread(os.path.join(forge_path, img_name), cv2.IMREAD_GRAYSCALE)
    img = cv2.resize(img, img_size)
    forge_images.append(img)

`forge_images = np.array(forge_images)`

# normalize the data
`real_images = real_images.astype('float32') / 255.0`

`forge_images = forge_images.astype('float32') / 255.0`

# Create labels for the real and forged signatures
`import numpy as np`

`num_real_images = len(real_images)`

`num_forge_images = len(forge_images)`

# Create labels for the real and forged signatures
`real_labels = np.zeros(num_real_images, dtype=int)`

`forge_labels = np.ones(num_forge_images, dtype=int)`

# Concatenate the real and forged images and labels

`X = np.concatenate((real_images, forge_images), axis=0)`

`y = np.concatenate((real_labels, forge_labels), axis=0)`

# Reshaping the Training Set
`import numpy as np`

# create dummy data
`X_train = np.random.rand(40, 128, 128)`

# add another dimension to the array
`X_train = np.expand_dims(X_train, axis=-1)`

# reshape the array
`X_train = X_train.reshape(X_train.shape[0], 128, 128, 1)`

`print(X_train.shape)  # output: (40, 128, 128, 1)`

![Screenshot 2024-09-05 230556](https://github.com/user-attachments/assets/94f1c7f3-1530-4140-b20c-c460e110a5f0)

# Reshaping the Test Set
import numpy as np

# create dummy data
`X_test = np.random.rand(40, 128, 128)`

# add another dimension to the array
`X_test = np.expand_dims(X_test, axis=-1)`

# reshape the array
`X_test = X_train.reshape(X_test.shape[0], 128, 128, 1)`

`print(X_train.shape)  # output: (40, 128, 128, 1)`
![Screenshot 2024-09-05 230556](https://github.com/user-attachments/assets/94f1c7f3-1530-4140-b20c-c460e110a5f0)

# Making the CNN model

`from tensorflow.keras.models import Sequential`

`from tensorflow.keras.layers import Conv2D, MaxPooling2D, Flatten, Dense, Dropout`

# Create a Sequential model
`model = Sequential()`

# Add a convolutional layer
`model.add(Conv2D(filters=32, kernel_size=(3,3), activation='relu', input_shape=(128, 128, 1)))`

# Add a max pooling layer
`model.add(MaxPooling2D(pool_size=(2,2)))`

# Add another convolutional layer
`model.add(Conv2D(filters=64, kernel_size=(3,3), activation='relu'))`

# Add another max pooling layer
`model.add(MaxPooling2D(pool_size=(2,2)))`

# Flatten the output from the convolutional layers
`model.add(Flatten())`

# Add a fully connected layer with 128 neurons and a relu activation function
`model.add(Dense(units=128, activation='relu'))`

# Add a dropout layer to reduce overfitting
`model.add(Dropout(rate=0.5))`

# Add the output layer with a sigmoid activation function
`model.add(Dense(units=1, activation='sigmoid'))`

# Print a summary of the model architecture
`model.summary()`

![Screenshot 2024-09-05 230825](https://github.com/user-attachments/assets/5e068fff-7878-41b6-b9fc-d0ae8d3393e9)

# Evaluating the Model
`from sklearn.model_selection import train_test_split`

`X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)`

`model.compile(optimizer='adam', loss='binary_crossentropy', metrics=['accuracy'])`

`history = model.fit(X_train, y_train, batch_size=32, epochs=10, validation_data=(X_test, y_test))`

![Screenshot 2024-09-05 230923](https://github.com/user-attachments/assets/9fe8f7d8-38f3-4dfc-9872-4fd2fa3f794a)

# Testing Loss and Accuracy
`test_loss, test_acc = model.evaluate(X_test, y_test)`

`print("Test accuracy:", test_acc)`

`print("Test loss:", test_loss)`

![Screenshot 2024-09-05 231041](https://github.com/user-attachments/assets/770e8d02-5a04-43c6-b3f2-208c14c6ce34)

# Detection of Real and Forged Signature
#Load a signature image
#You can change the image path and check if it is forged or real
`img = cv2.imread('/content/drive/MyDrive/dataset/orininal dataset/agh1_1.jpg', cv2.IMREAD_GRAYSCALE)`

`img = cv2.resize(img, (128, 128))`

`img = np.array(img).reshape(1, 128, 128, 1) / 255.0`

# Predict the class of the signature image
`prediction = model.predict(img)`

`if prediction < 0.5:`

    `print("The signature is real.")`

`else:`

   ` print("The signature is forged.")`

![Screenshot 2024-09-05 231212](https://github.com/user-attachments/assets/6fb5af4e-1741-45c1-b2e9-739e3df49efa)

![Screenshot 2024-09-05 231309](https://github.com/user-attachments/assets/06218b78-9b21-4ca9-8536-ebebb300716c)
