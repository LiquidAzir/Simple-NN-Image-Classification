
# Simple Neural Network Image Classification

This project demonstrates how to build a simple neural network for classifying images of cats and dogs using PyTorch. The model is trained to distinguish between the two classes using a small dataset of images.

## Project Structure

- **NN_Image_Classification.ipynb**: The main Jupyter Notebook that contains the code for the entire project.
- **data/**: Contains the dataset of cat and dog images (downloaded during the notebook execution).
- **models/**: Directory for saving trained models (if applicable).

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.7+
- Jupyter Notebook
- PyTorch
- torchvision
- matplotlib
- PIL (Python Imaging Library)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/LiquidAzir/Simple-NN-Image-Classification.git
   cd Simple-NN-Image-Classification
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

### Running the Project

Open the `NN_Image_Classification.ipynb` file in Jupyter Notebook or Google Colab and execute the cells in order. The notebook will guide you through the steps of downloading the dataset, preprocessing the images, defining the model, training it, and evaluating its performance.

### Dataset

The dataset consists of images of cats and dogs. The images are downloaded from a GitHub repository and are labeled based on their filenames.

### Model

The model is a simple feedforward neural network defined using PyTorch. The architecture and training details can be modified within the notebook.

### Results

After training, the model will output its performance metrics, including accuracy on the test set. Example predictions will also be shown.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or suggestions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
