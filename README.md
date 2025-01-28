# Milk Quality Classification with Neural Networks

This project aims to classify milk quality using a neural network model. The dataset includes various physical attributes of milk samples (pH, temperature, taste, odor, fat, turbidity, and color) and quality labels (low, medium, high).

## Technologies Used
- Python
- PyTorch
- Pandas
- NumPy
- scikit-learn

## Steps

1. **Data Preprocessing**: 
   - Loaded the dataset from a CSV file.
   - Converted the 'Grade' column into numerical labels.
   - Split the data into training, validation, and test sets.
   - Standardized the feature columns.

2. **Model Architecture**:
   - Input layer: 7 features (pH, temperature, taste, odor, fat, turbidity, color).
   - Two hidden layers: 64 and 32 neurons with ReLU activation.
   - Output layer: 3 neurons for classifying into 'low', 'medium', 'high' using Softmax.

3. **Model Training**:
   - Used Cross-Entropy loss and Adam optimizer.
   - Trained for 50 epochs, tracking training loss and validation accuracy.

## Dataset
- **Features**: pH, temperature, taste, odor, fat, turbidity, color.
- **Target**: Grade (low, medium, high).

## Results
- Achieved 99.06% validation accuracy after 50 epochs.

