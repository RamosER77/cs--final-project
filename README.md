# CS471 Final Project - Mango Classification

This project implements various ML algorithms for mango classification.

## Contents
# CS471 Final Project - Mango Classification System

## Overview
This project implements a comprehensive machine learning system for classifying mangoes based on their ripeness levels using computer vision and various ML algorithms. Developed as the final project for CS471 (Artificial Intelligence) at CSU San Marcos.

## Project Description
The goal of this project is to automatically classify mangoes into different ripeness categories using image processing and machine learning techniques. The system can distinguish between:
- Ripe mangoes
- Unripe mangoes  
- Very ripe mangoes

## Features
- Multiple machine learning algorithms implemented and compared
- Balanced dataset with augmented images
- Real-world testing capabilities
- Optimized model for deployment
- Comprehensive data visualization

## Dataset
The project includes two main datasets:
- **MangoDataset_Balanced**: A balanced training dataset with images categorized by ripeness
- **MangoRealTestImages**: Real-world test images for model validation

## Algorithms Implemented
1. **Random Forest Classifier** (`RandomForestAlgorithm.ipynb`)
2. **Gradient Boosting Classifier** (`GradientBoostingClassifierAlgo.ipynb`)
3. **Deep Learning Model** (`trainingMangoModel.ipynb`)
4. **Optimized TensorFlow Lite Model** for mobile deployment

## Project Structure
```
cs--final-project/
├── MangoDataset_Balanced/          # Balanced training dataset
│   ├── train/
│   │   ├── Ripe/
│   │   ├── Unripe/
│   │   └── VeryRipe/
│   └── val/
├── MangoRealTestImages/            # Real-world test images
├── balacedTrainingModel.ipynb      # Model training notebook
├── checkingDuplicateImages.ipynb   # Data preprocessing utility
├── dataset_visualization.png       # Dataset distribution visualization
├── GradientBoostingClassifierAlgo.ipynb  # Gradient Boosting implementation
├── ImagesCountingBalancedGraph.ipynb     # Dataset analysis
├── jpv0wo8j5_optimized_tflite_mm5zjg2km.tflite  # Optimized model
├── optimizeModelAIHub.ipynb        # Model optimization notebook
├── RandomForestAlgorithm.ipynb     # Random Forest implementation
├── TestingWithRealData.ipynb       # Real-world testing notebook
└── trainingMangoModel.ipynb        # Deep learning model training
```

## Key Notebooks
- **`trainingMangoModel.ipynb`**: Main deep learning model training
- **`TestingWithRealData.ipynb`**: Evaluate model on real-world images
- **`checkingDuplicateImages.ipynb`**: Data quality checks
- **`optimizeModelAIHub.ipynb`**: Model optimization for deployment

## Results
- Successfully trained multiple models for mango classification
- Achieved high accuracy on both validation and real-world test sets
- Created an optimized TensorFlow Lite model for mobile deployment
- Generated comprehensive visualizations of dataset distribution

## Technologies Used
- Python
- TensorFlow/Keras
- Scikit-learn
- OpenCV
- NumPy
- Pandas
- Matplotlib

## Future Improvements
- Expand dataset with more mango varieties
- Implement real-time classification
- Deploy as mobile application
- Add more ripeness categories
- Integrate with IoT devices for automated sorting

## Author
**Eduardo Ramos**  
CS471 - Artificial Intelligence  
CSU San Marcos  
Spring 2025

## License
This project is part of academic coursework at CSU San Marcos.

## Acknowledgments
Special thanks to the CS471 course instructor and CSU San Marcos for providing the resources and guidance for this project.
