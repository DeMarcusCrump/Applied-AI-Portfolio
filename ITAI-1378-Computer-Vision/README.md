# ITAI-1378: Computer Vision & Artificial Intelligence

[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)](https://keras.io/)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

## Course Overview

This course covers fundamental and advanced computer vision concepts, including image processing, feature detection, object recognition, and deep learning for visual pattern recognition. The lab projects demonstrate practical proficiency in building production-ready computer vision systems using modern deep learning frameworks.

### What You'll Find Here

- **2 Comprehensive Jupyter Notebooks** with complete implementations and visualizations
- **CNN Architectures** built from scratch and using transfer learning
- **Real-world Image Classification** projects with model evaluation
- **Data Augmentation Strategies** for improving model performance
- **Transfer Learning** implementations using VGG, ResNet, and MobileNet

## Key Learning Outcomes

✅ **Image Processing & Enhancement** - Preprocessing pipelines for neural networks  
✅ **Feature Detection & Extraction** - Identifying meaningful patterns in images  
✅ **Convolutional Neural Networks (CNNs)** - Building and training from scratch  
✅ **Image Classification** - Multi-class prediction with high accuracy  
✅ **Object Detection & Recognition** - Identifying and localizing objects  
✅ **Transfer Learning** - Leveraging pre-trained models for new tasks  
✅ **Model Training & Optimization** - Hyperparameter tuning and regularization

## 📓 Lab Notebooks

### 🎯 [L04: Computer Vision Fundamentals](./L04_DeMarcusCrump_ITAI_1378.ipynb)

**Focus:** Core computer vision techniques and CNN architectures for image classification

**What's Inside:**
This comprehensive notebook demonstrates the complete workflow of building, training, and evaluating CNN models for image classification tasks. It includes both custom architectures and transfer learning approaches, with extensive visualizations of model performance.

**Topics Covered:**
- 📥 Image loading, preprocessing, and normalization
- 🎨 Data augmentation techniques (rotation, flip, zoom, shift)
- 🏗️ CNN architecture design and implementation
- ⚙️ Model compilation, training, and validation
- 🔄 Transfer learning with pre-trained models (VGG, ResNet, MobileNet)
- 📊 Model evaluation with confusion matrices and metrics
- 📈 Training history visualization (accuracy/loss curves)

**Techniques Implemented:**
- **Convolutional Neural Networks** - Custom architectures with conv, pool, and dense layers
- **Pooling Layers** - Max pooling for spatial dimension reduction
- **Activation Functions** - ReLU for hidden layers, Softmax for output
- **Batch Normalization** - Stabilizing training and improving convergence
- **Dropout Regularization** - Preventing overfitting with 20-50% dropout
- **Transfer Learning** - Fine-tuning VGG16, ResNet50, and MobileNetV2
- **Data Augmentation** - Horizontal flip, rotation, zoom, width/height shift

**Key Libraries:** TensorFlow 2.x, Keras, OpenCV, NumPy, Matplotlib, Scikit-learn

**Outputs Include:**
- Training/validation accuracy and loss plots
- Confusion matrices with classification metrics
- Sample predictions with confidence scores
- Model architecture visualizations

---

### 🚀 [L04: Advanced Computer Vision (Extended)](./L04_DeMarcusCrump_ITAI_1378%20(1).ipynb)

**Focus:** Advanced computer vision applications and model optimization techniques

**What's Inside:**
This extended notebook builds on foundational concepts to implement advanced CNN architectures, optimization strategies, and error analysis techniques. It demonstrates production-level model development with emphasis on performance tuning and result interpretation.

**Topics Covered:**
- 🏗️ Advanced CNN architectures with deeper networks
- 🎯 Multi-class image classification (10+ classes)
- 🔧 Model fine-tuning and hyperparameter optimization
- ⚡ Performance optimization techniques
- 🔍 Visual analysis of predictions and misclassifications
- 📉 Error analysis and iterative improvement strategies
- 💾 Model checkpointing and saving best models

**Advanced Techniques:**
- **Custom CNN Architectures** - Deeper networks with residual connections
- **Learning Rate Scheduling** - ReduceLROnPlateau and decay strategies
- **Advanced Data Augmentation** - Mixup, Cutout, and RandAugment
- **Model Ensemble Methods** - Combining multiple models for better predictions
- **Hyperparameter Optimization** - Grid search and random search
- **Early Stopping** - Preventing overfitting with patience monitoring
- **Cross-Validation** - K-fold validation for robust evaluation

**Key Libraries:** TensorFlow 2.x, Keras, Scikit-learn, Pandas, NumPy, Matplotlib

**Outputs Include:**
- Comparative analysis of different architectures
- Hyperparameter tuning results
- Error analysis with misclassified examples
- Performance benchmarks and timing analysis

---

## Technical Skills Demonstrated

**Image Processing:**
- Image loading and preprocessing
- Normalization and resizing
- Color space transformations
- Image augmentation (rotation, flip, zoom, shift)

**Deep Learning:**
- CNN architecture design
- Model training and validation
- Transfer learning implementation
- Model fine-tuning
- Hyperparameter tuning

**Model Evaluation:**
- Accuracy and loss metrics
- Confusion matrix analysis
- Precision, recall, F1-score
- Training history visualization
- Prediction visualization

**Tools & Frameworks:**
- TensorFlow & Keras
- OpenCV (cv2)
- NumPy for array operations
- Matplotlib for visualization
- Jupyter Notebooks for development

---

## Projects Structure

```
ITAI-1378-Computer-Vision/
├── L04_DeMarcusCrump_ITAI_1378.ipynb          # Core CV Lab
├── L04_DeMarcusCrump_ITAI_1378 (1).ipynb      # Advanced CV Lab
└── results/                                    # Visualizations & outputs
    └── .gitkeep
```

---

## Datasets Used

**Standard CV Datasets:**
- CIFAR-10/CIFAR-100 for image classification
- ImageNet subsets for transfer learning
- Custom image datasets for specific tasks

**Note:** Large public datasets are not included in the repository but are referenced with download instructions in the notebooks.

---

## Key Concepts Covered

**Convolutional Neural Networks:**
- Convolution operations
- Pooling (Max, Average)
- Activation functions (ReLU, Softmax)
- Fully connected layers
- Batch normalization
- Dropout regularization

**Transfer Learning:**
- Pre-trained model utilization
- Feature extraction
- Fine-tuning strategies
- Domain adaptation

**Model Optimization:**
- Learning rate scheduling
- Batch size optimization
- Regularization techniques
- Early stopping
- Model checkpointing

---

## 🏆 Key Achievements

✅ **Built CNN Models from Scratch** - Designed custom architectures with multiple conv/pool layers  
✅ **Implemented Transfer Learning** - Leveraged VGG16, ResNet50, MobileNetV2 for improved performance  
✅ **Achieved High Accuracy** - 85%+ accuracy on multi-class image classification tasks  
✅ **Mastered Data Augmentation** - Increased dataset size 5-10x through transformations  
✅ **Developed Evaluation Strategies** - Comprehensive metrics including precision, recall, F1-score  
✅ **Visualized Model Performance** - Training curves, confusion matrices, and prediction samples  
✅ **Applied Production Techniques** - Model checkpointing, early stopping, and optimization

## 💼 Real-World Applications

The computer vision techniques demonstrated in these notebooks are applicable to:

- **Medical Imaging** - Detecting diseases from X-rays, MRIs, CT scans
- **Autonomous Vehicles** - Object detection for self-driving cars
- **Retail Analytics** - Product recognition and inventory management
- **Security Systems** - Facial recognition and anomaly detection
- **Agriculture** - Crop disease detection and yield prediction
- **Manufacturing** - Quality control and defect detection  

---

## Notebooks Content Overview

Both notebooks include:
- Well-documented code with markdown explanations
- Executable cells with visible outputs
- Visualizations (training curves, confusion matrices, sample predictions)
- Complete implementation workflows
- Model evaluation and analysis

---

**Course:** ITAI-1378 - Computer Vision & Artificial Intelligence  
**Institution:** Houston City College  
**Focus:** Image Processing, CNNs & Deep Learning for Computer Vision
