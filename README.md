##  👥 Crowd-Density-Detection
This project is based on a Deep learning-based crowd density estimation system using CrowdNet CNN architecture to analyze crowd images, generate density maps via Gaussian filter transformation, and classify public spaces as safe or unsafe based on predicted crowd counts with safety threshold categorization.

### 🎯 Key Features
___
- Implements CrowdNet CNN architecture for spatial feature extraction from crowd images.
- Analyzes two image datasets for crowd density estimation: **ShanghaiTech Dataset (1198 images) and the Mall Dataset (2000 images)**
- Generates density maps using Gaussian Filter Transformation.
- Safe vs. Unsafe crowd levels based on threshold analysis

### ⚙️ Tech Stack
___
- **Python** - Primary programming language
- **TensorFlow/Keras** - Deep learning framework for CNN implementation
- **OpenCV** - Image Processing and Transformation
- **Pandas** - Data manipulation and preprocessing
- **NumPy** - Numerical computing and array operations
- **Matplotlib / Seaborn** - Data visualization
- **scikit-image** - Gaussian filter transformation for density maps

### 💪 How it Works?
___
#### Data Collection
- Utilized the ShangahiTech Image Dataset and the Mall Image Dataset containing crowd scenes.
- Images captured different crowd densities, lighting conditions, and environments.
- The dataset includes both safe and unsafe crowd density scenarios. <br>

📁Get the Data <br>

[<kbd>ShanghaiTech Dataset</kbd>](https://www.kaggle.com/datasets/tthien/shanghaitech)
[<kbd>Mall Dataset</kbd>](https://www.kaggle.com/datasets/chaozhuang/mall-dataset)

#### Data Preprocessing
- Resized and normalized crowd images for consistent input dimensions.
- Applied Gaussian Filter Transformation to generate density maps from crowd images.

#### Model Comparison and Training
- Implemented CrowdNet CNN architecture designed for crowd analysis.
- Pooling layers reduce dimensionality while preserving critical spatial information.

#### Crowd Density Prediction
- Model processes input crowd images through CrowdNet architecture
- Generates predicted crowd counts and density estimates
- Density maps visualize spatial distribution of people in the scene
- Outputs numerical crowd count predictions for each image

#### Safety Classification
- Established safety threshold based on crowd density analysis.

#### Performance Evaluation
- Tested model on separate test dataset to evaluate generalization.

#### Visualization
- Scatter plots: Actual vs. Predicted crowd counts showing model accuracy.
- Density map visualizations highlighting crowd concentration areas.
____

#### Design Framework

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/366e8ef0-fe6b-41f1-9731-c30b779d5764" />

____
### 🏆Key Findings
CrowdNet CNN successfully estimates crowd density 
____

### Applications
- Real-time monitoring of public events (concerts, sports, festivals)
- Smart city surveillance for crowd management
- Emergency evacuation planning and response
- Public transportation safety monitoring
____

### <ins>Screenshots</ins>
**Density Map Generation**

<img width="270" height="150" alt="image" src="https://github.com/user-attachments/assets/542117ea-2e06-43d9-90ef-039db82255fc" />
<img width="270" height="150" alt="image" src="https://github.com/user-attachments/assets/4611afdb-b3e7-4465-aeb9-2dbb1a975668" /><br><br>

<img width="270" height="160" alt="image" src="https://github.com/user-attachments/assets/27960c7f-09aa-4679-af2e-79e71907ade5" />
<img width="270" height="160" alt="image" src="https://github.com/user-attachments/assets/fc450742-6ae1-488c-83a7-7883bf59e55e" /><br>


**Model Training:**

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/92038c56-9d10-4e14-ba80-beb436348b29" /> <br><br>
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/767db77c-28f5-4f86-b723-7ae37221e8a0" /><br>

**Model Testing:**

<img width="270" height="150" alt="image" src="https://github.com/user-attachments/assets/cd20c2b9-c768-41b2-9021-2df163df3dff" />
<img width="270" height="150" alt="image" src="https://github.com/user-attachments/assets/eccbf213-f52b-4ddc-a61a-971008aa38a7" /><br><br>

<img width="270" height="150" alt="image" src="https://github.com/user-attachments/assets/1e61d1ce-8591-4faa-8828-21b7617b6a6e" />
<img width="270" height="150" alt="image" src="https://github.com/user-attachments/assets/cfb37c62-7b9b-4442-98ae-2bac5fc1b0b0" />


#### **"Data Access: Due to licensing and privacy considerations, datasets are not included in this repository."**
