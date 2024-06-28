# MNIST Digit Classification using PyTorch

This project implements a convolutional neural network (CNN) in PyTorch to classify handwritten digits from the MNIST dataset. The implementation is done in a Jupyter Notebook (`main.ipynb`), covering data loading, preprocessing, model architecture, training, evaluation, and visualization of results.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Folder Structure](#folder-structure)
5. [Project Details](#project-details)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

---

## Project Overview

The notebook `main.ipynb` contains Python code to build and train a deep learning model that classifies images of handwritten digits (0-9) from the MNIST dataset. It includes:

- **Dataset:** Utilizes the MNIST dataset provided by torchvision, consisting of 60,000 training images and 10,000 validation images.

- **Model Architecture:** Implements a custom CNN architecture using PyTorch's nn.Module.

- **Training:** Trains the model using stochastic gradient descent (SGD) optimizer with Cross Entropy Loss, evaluating training loss after each epoch.

- **Evaluation:** Evaluates the trained model on a separate validation set to measure accuracy.

---

## Installation

As the project is implemented in a Jupyter Notebook, there's no need for installation beyond having Python and necessary libraries like PyTorch and torchvision installed on your system.

---

## Usage

### Opening the Notebook

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/mnist-digit-classifier.git
   cd mnist-digit-classifier
   ```

2. Launch Jupyter Notebook and open `main.ipynb`:
   ```bash
   jupyter notebook main.ipynb
   ```

### Running the Notebook

- Execute each cell in `main.ipynb` sequentially to follow the project flow from data loading to model evaluation.

---

## Folder Structure

Assuming everything is in the notebook, the folder structure could look like this:

```
mnist-digit-classifier/
│
├── main.ipynb           # Jupyter Notebook containing the project implementation
├── data/                # Placeholder for any additional data or resources
└── README.md            # Project overview and documentation (you're here!)
```

---

## Project Details

- **Data Preprocessing:** MNIST images are normalized and transformed using torchvision transforms directly within the notebook.

- **Model Architecture:** Defined within the notebook using PyTorch's nn.Module, consisting of convolutional layers followed by fully connected layers for classification.

- **Training and Evaluation:** The notebook includes sections for training the model, evaluating its performance on the validation set, and visualizing results like loss curves and accuracy metrics.

---

## Results

The trained model achieves an accuracy of 98.76% on the MNIST validation set, demonstrating its effectiveness in classifying handwritten digits.

---

## Contributing

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
