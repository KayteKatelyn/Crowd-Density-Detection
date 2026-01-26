##  👥 Crowd-Density-Detection
> Deep learning-based crowd density estimation system using CrowdNet CNN architecture to analyze crowd images, generate density maps via Gaussian filter transformation, and classify public spaces as safe or unsafe based on predicted crowd counts with safety threshold categorization.

### 🎯 Key Features
- Implements CrowdNet CNN architecture for spatial feature extraction from crowd images.
- Analyzes two image datasets for crowd density estimation: **ShanghaiTech Dataset (1198 images) and the Mall Dataset (2000 images)**
- Generates density maps using Gaussian Filter Transformation.
- Safe vs. Unsafe crowd levels based on threshold analysis

### ⚙️ Tech Stack
- **Python** - Primary programming language
- **TensorFlow/Keras** - Deep learning framework for CNN implementation
- **OpenCV** - Image Processing and Transformation
- **Pandas** - Data manipulation and preprocessing
- **NumPy** - Numerical computing and array operations
- **Matplotlib / Seaborn** - Data visualization
- **scikit-image** - Gaussian filter transformation for density maps


### 💪 How it Works?

#### Data Collection
- Utilized the ShangahiTech Image Dataset and the Mall Image Dataset containing crowd scenes.
- Images captured different crowd densities, lighting conditions, and environments.
- The dataset includes both safe and unsafe crowd density scenarios.

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

### 🏆Key Findings
CrowdNet CNN successfully estimates crowd density 

### Applications:
- Real-time monitoring of public events (concerts, sports, festivals)
- Smart city surveillance for crowd management
- Emergency evacuation planning and response
- Public transportation safety monitoring

### **Data Access: Due to licensing and privacy considerations, datasets are not included in this repository.**
