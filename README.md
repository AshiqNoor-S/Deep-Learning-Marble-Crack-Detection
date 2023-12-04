# Deep Learning: Marble Crack Detection

## Overview

This repository contains the code and documentation for my deep learning capstone project, where I applied deep learning techniques to address the challenge of crack detection in marble images. I implemented two models, one using VGG16 and the other using ResNet50, and compared their performance.

## Project Structure

- **`Data/`**: Contains the dataset used for training and testing.
- **`Notebooks/`**: Jupyter notebooks for data exploration, model development, and evaluation.
- **`Models/`**: Saved model files after training.
- **`Comparison and Testing/`**: Results and performance metrics.

## Libraries Used

- **Keras**: Used for building and training deep learning models.
- **Matplotlib**: Used for data visualization and plotting.
- **NumPy**: Used for numerical operations and array manipulation.
- **Pandas**: Used for data manipulation and analysis.
- **os**: Used for interacting with the operating system.

## Usage

1. **Data Preparation**: Ensure the dataset is in the `data/` directory.

2. **Model Training**: Use the Jupyter notebooks in the `notebooks/` directory to train the VGG16 and ResNet50 models.

3. **Evaluation**: View the model performance metrics in the `results/` directory.

## Model Performance

### VGG16 Performance

- Accuracy: 99.57%
- Loss: 0.01698

### ResNet50 Performance

- Accuracy: 99.94%
- Loss: 0.00302

## Results and Insights

In analyzing the model performance, both VGG16 and ResNet50 achieved high accuracy rates, demonstrating their effectiveness in marble crack detection. Visualizations in the notebooks reveal the successful identification of cracks in test images.

## Conclusion

The results indicate that deep learning models, specifically VGG16 and ResNet50, can be valuable tools for marble crack detection. The application of these models can contribute to early detection and preventive maintenance in industries where marble is widely used.

## Future Work

Future work could involve fine-tuning hyperparameters, exploring additional data augmentation techniques, or considering transfer learning from models trained on larger datasets. Additionally, collaboration with domain experts to enhance model interpretability is a potential avenue for improvement.

## Author
Ashiq Noor Sudheer

